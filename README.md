## Validation

Pull requests and `main` use the shared repository-validation contract.
Secret-free preflight parses every draw.io file and rejects malformed diffs;
portable validation checks the documented diagram structure. The required
aggregate status is
`Repository validation / Background-safe repository checks`.
