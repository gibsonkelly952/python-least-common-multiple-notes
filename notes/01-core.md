# Compute a least common multiple: implementation

## What the example does

lcm returns zero if either argument is zero. For nonzero integers the result is positive regardless of argument signs.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
[
  12,
  18
]
```

Expected result:

```json
36
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
