# AX — Liquidity Without Liquidations

**AX** is a collateralized liquidity protocol designed to provide liquidity
without price-based liquidations, price oracles, or governance intervention.

AX focuses on deterministic rules, mandatory position finalization,
and market-driven settlement via buyback & burn.

---

## Table of Contents

- [Overview](#overview)
- [How AX1 Works](#how-ax1-works)
- [Core Principles](#core-principles)
- [Protocol Flow](#protocol-flow)
- [AX1 Specification](#ax1-specification)
- [AXP Pre-Token](#axp-pre-token)
- [Project Status](#project-status)
- [Links & Community](#links--community)
- [Disclaimer](#disclaimer)

---

## Overview

**AX1** is the first implementation of the AX protocol.

It allows users to lock SOL as collateral and obtain liquidity
without the risk of forced liquidation due to price volatility.

Key idea:

> Liquidity without liquidations.  
> No price oracles. No governance. Mandatory finalization.

---

## How AX1 Works

1. A user deposits SOL as collateral  
2. AX is minted with a fixed LTV (90%)  
3. AX can be freely used or traded  
4. The position is finalized in one of two ways:
   - Voluntary redeem by the user
   - Automatic market buyback and burn by the protocol

Every position **must** reach final settlement.

---

## Core Principles

- No price oracles
- No price-based liquidations
- Immutable parameters
- Mandatory position finalization
- Buyback & burn as the only settlement mechanism

AX does not attempt to predict or control market prices.
It enforces rules and lets the market resolve outcomes.

---

## Protocol Flow

### High-Level Lifecycle


