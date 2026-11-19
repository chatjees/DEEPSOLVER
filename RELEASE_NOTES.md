# DEEPSOLVER 0.8 engineering preview

- Rebrands the independent desktop product as DEEPSOLVER.
- Retains local model interpretation, DCB setup, reviewed APDL execution, plots and Excel output.
- Adds Ed25519-signed device-bound activation-file verification before solver execution.
- Adds an operator-side trial issuer that preserves the first activation's 10-day end date.
- Prepares four INR subscription periods and Razorpay server-side integration components.

Automatic public trial activation, merchant checkout, paid renewal/revocation and account management remain undeployed. The included licence verification key is a development key; production key management is not complete.

Twelve automated product/licensing checks passed, including expiration, input tampering, device binding, trial repeat issuance, calendar periods, price amounts and raw-body webhook signatures. No Ansys solver was executed for this release. Clean second-machine installation and broader Ansys compatibility remain unverified.
