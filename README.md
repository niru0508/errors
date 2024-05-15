# SoftwareProject Contract

This Solidity contract represents a Software Project, providing functionalities to manage developer approvals and eligibility for contributing to the project.

## Overview

The `SoftwareProject` contract facilitates the management of developers' approvals and eligibility for a software project. It includes the following main features:

- Approval Committee: Developers can approve the project and set the number of developers involved.
- Developer Eligibility: Determines whether a developer meets the experience requirements to contribute to the project.

## Usage

### Approval Committee

The `approvalCommittee` function allows members of the approval committee to set the number of developers approving the project and the project year. If the number of approving developers is equal to or greater than 10, the project is considered a release candidate.

### Developer Eligibility

The `developerEligibility` function checks if a developer meets the minimum experience requirement of 3 years to contribute to the project.

## Requirements

- Solidity version ^0.8.0

## Deployment

Deploy this contract to your preferred Ethereum Virtual Machine (EVM) compatible blockchain.

## License

This project is licensed under the terms of the MIT License.

## Disclaimer

This contract is provided as a sample for educational purposes only. It may not be suitable for use in production environments without further testing and modifications.

