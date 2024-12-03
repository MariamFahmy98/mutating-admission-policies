This repository contains MutatingAdmissionPolicies (MAPs) that serve as alternatives to Kyverno's mutating policies.

MutatingAdmissionPolicies are created for Kyverno policies that include the following features:
- Add if not present anchor
- Conditional anchor
- Global anchor
- Global combined with Add anchor
- Foreach with JSONPatch
- Foreach with a conditional anchor
- Nested Foreach