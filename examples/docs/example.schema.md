---
template: reference
foo: bar
---

# Example Schema

```
https://example.com/schemas/example
```

This is an example schema with examples. Too many examples? There can never be too many examples!

| Abstract | Extensible | Custom Properties | Additional Properties | Defined In |
|----------|------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Forbidden | Permitted | [example.schema.json](example.schema.json) |

## Example Example
```json
{
  "foo": "bar",
  "bar": "baz"
}
```

# Example Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [bar](#bar) | `string` | Optional | Example (this schema) |
| [foo](#foo) | `string` | Optional | Example (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## bar

A simple string.

`bar`
* is optional
* type: `string`
* defined in this schema

### bar Type


`string`





### bar Examples

```json
"bar"
```

```json
"baz"
```



## foo

A simple string.

`foo`
* is optional
* type: `string`
* defined in this schema

### foo Type


`string`





### foo Example

```json
"bar"
```

