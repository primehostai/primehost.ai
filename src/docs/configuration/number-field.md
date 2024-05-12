---
title: Number field
---

A field for numerical values (anya valid floating point number).

## Options

| Option | Type | Description |
| - | - | - |
| **`min`** | `string` | If defined, sets the minimum value for the field. |
| **`max`** | `string` | If defined, sets the maximum value for the field. |
| **`step`** | `string` | Defines the granularity of values. Behavior is the same as step for a [number input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/number). |

## Example

```yaml
- name: age
  label: Age
  options:
    min: 21
```