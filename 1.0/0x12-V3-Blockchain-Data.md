# V3: Blockchain data

## Control Objective

Ensure that a verified contract satisfies the following high level requirements:
* TODO

Category “V3” lists requirements related to the blockchain data of the smart contracts.

## Security Verification Requirements

| # | Description | Since |
| --- | --- | --- |
| **3.1** | Verify that any data saved in contracts is not considered safe or private (even private variables). | 1.0 |
| **3.2** | Verify that no confidential data is stored in the blockchain (passwords, personal data, token etc.) | 1.0 |
| **3.3** | Verify that the list of sensitive data processed by the smart contract is identified, and that there is an explicit policy for how access to this data must be controlled and enforced under relevant data protection directives. | 1.0 |
| **3.4** | Verify that there is a component that monitors access to sensitive contract data using events. | 1.0 |
| **3.5** | Verify that contract does not use string literals as keys for mappings. Verify that global constants are used instead to prevent homoglyphs attacks. | 1.0 |


## References

For more information, see also:

* [Homoglyph attack](https://github.com/Arachnid/uscc/tree/master/submissions-2017/marcogiglio)