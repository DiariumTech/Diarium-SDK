# Diarium SDK

A production-grade SDK for interacting with Diarium on-chain infrastructure.

Diarium is a Solana-native system designed to structure, index, and execute on-chain activity in a deterministic and verifiable manner.  
This SDK provides a clean interface for developers to integrate Diarium programs into backend services, bots, and protocol-level applications.

---

## Overview

The Diarium SDK abstracts low-level Solana interactions while preserving explicit control over transaction construction and execution flow.

It is built for environments that require reliability, transparency, and composability—without hiding protocol mechanics behind opaque abstractions.

---

## Repository Structure


---

## SDK Scope

This repository focuses on the **client-side interface** of the Diarium protocol.

It includes:
- Deterministic transaction builders
- Program instruction composition
- Account and PDA derivation helpers
- Type-safe abstractions for protocol interaction

The on-chain programs are maintained separately and treated as immutable protocol primitives.

---

## Usage

The SDK is intended for server-side or controlled execution environments.

```ts
