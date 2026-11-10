# Session notes

- `stdlib-candidate-archive/tests/test_aggregate.nu` fails to parse on Nu
  0.117.0 with `nu::parser::output_type_mismatch` around line 134: a
  function declared to return `error` outputs a `list<any>` or `table`.
  Present on upstream `main` as well.
