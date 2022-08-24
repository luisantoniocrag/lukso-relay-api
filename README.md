# LUKSO API Relay Service 🐝

## Description
### Overview
### Presentation
### Video Demo
### Problem to solve
### Solution

## These are the requirements for the hackathon
- [ ] Develop an API service that can pay for users transactions using the [LSP6 KeyManager](https://docs.lukso.tech/standards/universal-profile/lsp6-key-manager/) [executeRelayCall()](https://github.com/lukso-network/LIPs/blob/main/LSPs/LSP-6-KeyManager.md#executerelaycall) function.
- [ ] The API needs to be based on the [Transaction Relay Service API standard](https://www.notion.so/Transaction-Relay-Service-API-Standard-2bda58f4f47f4497bb3381654acda8c3).
- [ ] The service can be subscription based with a free allowance for new users (or based on any other business model). This should be developed as a business that can be run in the future.
- [ ] You need a dashboard for users to login via their UP to signup for the service. The service could also offer to create users UPs. In the dashboard, users should be able to pay for transactions monthly and select a number of UPs they want to use the service with.
- [ ] Aspects to consider carefully are: nonce handling, account refilling, transaction queuing, transaction hash generation.
- [ ] For testing, a dummy website could be built that controls a user's UP, later we will allow adding relay services to the UP extension using a RPC method like `up_addRelayService;` `params=name,` `website`, `APIurl`

## Use cases

- User withdraws tokens without FEE cryptocurrency
- User sends tokens without the base FEE cryptocurrency

## How to run the project

## What is next?
