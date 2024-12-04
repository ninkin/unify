# unify

Modifies strings to all use the same quote where possible.

## Example

After running:

```bash
$ unify --in-place example.py
```

this code

```python
x = "abc"
y = 'hello'
```

gets formatted into this

```python
x = 'abc'
y = 'hello'
```