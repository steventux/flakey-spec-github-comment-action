# Flakey spec Github comment action

Creates a comment on a Github issue or pull request concerning flakey tests found in the preceding test run.

Expects a comma-delimited data format of:

```
<failed attempts [Integer]>, <maximun number of failed attempts [Integer]>, <spec file and line number [String]>, <error messages [Array]>
```
