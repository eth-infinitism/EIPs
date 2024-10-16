---
eip:
title: Reserve Transaction Types 100-110 for the RIP Coordination Process
description: Reserve Transaction Types 100-110 for the RIP Coordination Process
author:
discussions-to:
status: Draft
type: Standards Track
category: Core
created:
requires:
---

## Abstract

This EIP proposes the reservation of transaction types 100-110 within the Ethereum protocol for the purpose
of standardizing Rollup transactions as part of the RIP coordination process.

The reservation will help facilitate the development of Rollup solutions and encourage compatibility
across various implementations.

## Motivation

Rollups are a promising scalability solution for Ethereum, allowing for the batching of transactions and
off-chain computation while ensuring security through Ethereum's layer-1.

As Rollup solutions evolve, there is a need for standardization to ensure interoperability,
enhance developer experience, and promote ecosystem growth. Reserving transaction types specifically
for Rollups will help establish a clear framework for these innovations.

## Specification

### Transaction Type Reservation

Transaction types 100 through 110 will be reserved exclusively for Rollup-related transactions.

These transaction types cannot be used by Ethereum Layer-1 or any other EVM-compatible Layer-2 solutions
unless the transaction type has been properly assigned by a corresponding RIP document.

## Rationale

By reserving specific transaction types, developers can create a consistent framework for Rollup solutions,
enabling easier integration, testing, and user experience.

This proactive approach will also minimize the risk of conflicts with other transaction types and ensure
that future developments are aligned.

## Copyright

Copyright and related rights waived via CC0 1.0 Universal.
