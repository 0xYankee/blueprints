# Switchboard Token

## Main Objective
- Launch a Switchboard Token for operational usage such as fees, oracles
  incentives and stake.
- Implement a Points system for participants of the Switchboard Network.

## Background
Switchboard is a TEE-oracle protocol providing a service for developers 
to access off-chain data and computational resources. Currently, the only 
economic flow existing in our protocol is for usage, incentives and oracle 
stake.

- Usage: Users top up in a LeaseAccount to readily pay out transaction fees
  and incentives to oracles that execute their requests.
- Incentives: Oracles are tasked to execute and receive a cut for their
  honesty and timely executions.
- Oracle Stake: In order for oracles to participate in a queue, oracles are
  required to stake a minimum amount and will be slashed if they misreport
  outside of defined data boundaries.

These economic components are currently being utilized in each chain’s 
native token, and we’re looking at the idea of implementing a Switchboard 
multichain token to facilitate and potentially bring more use cases to the 
tokens such as a points system for protocols to implement.

### What is Points?
Points is in reference to what [MarginFi](https://twitter.com/marginfi/status/1675863618666270722) 
is doing, it’s basically a points system where you earn from engaging 
on their platform like depositing x amount or borrowing, etc. A similar 
concept can be utilized for Switchboard, where a points system is used 
to track:

- Amount of fees/incentives paid per authority
- Amount of updates executed by oracle
- Amount of extendeded usage executed by authority's users
  (e.g. Mango's users utilizing a market supported by a Switchboard Feed)

## Context and Scope
The Switchboard Token will be:

- A multi-chain token utilizing LayerZero's OFT (Omni-Fungible Token) contracts. 
- Launching initially on ...
- 

## Initial team review
- Since our token is an OFT, do we only support LZ-supported chains?
- For non LZ-supported chains, will we stick to native tokens?
- Do we want the tokens to be transferrable or locked?
- What is the onboarding process for oracles and users to buy SBTokens?
- Will there be a new incentive scheme/percentage for oracles?
- Will there be added marginal fees for revenue extraction for Switchboard?
- Will there be a referral program on top of the tokens?
- Is the Points system something we should pursue in the perspective of a
  infrastructure middleware protocol that focuses on developer acquisition?

## Goals and non-Goals
Yet to review

## Technical Design
Yet to review

## Interface Designs
Yet to review

## Architecture Diagram(s)
Yet to review

## SDKs
Yet to review

## Alternatives Considered
Yet to review

## Related Work
Yet to review

## Estimated Timeline
Yet to review

## Go-To-Market Plan
Yet to review
