## Primitives

### **bool** ()
Arguments: None

Represents a boolean, encoded in one byte.

Example of value: `true` / `false`

### **cstring** ({ ?encoding: String })
Arguments: encoding

Represents a null terminated string. Similar to strings in C.
Assumes UTF-8 encoding by default

Example:
A UTF-16 string of unknown size that is expected to end with the zero character (null-terminal).
```json
[
  "cstring", { "encoding": "utf-16" }
]
```

Example of value: `"my string"`

### **void** ()
Arguments: None

Represents an empty value.

Example of value: `undefined` / `null`
