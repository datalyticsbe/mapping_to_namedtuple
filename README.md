Convertor Python Mapping to namedtuple
===

This project contains a function that converts a python mapping or dict to a namedtuple. 
The conversion works recursively and the input can contain other mappings or lists.


Usage
===

```python
mapping = {"a": "b", "c": "d"}

namedtuple = mapping_to_named_tuple(mapping, "test_tuple")
```

