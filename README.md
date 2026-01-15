# AX — Protocol Overview

**AX** is a collateralized liquidity protocol designed to provide liquidity
without price-based liquidations.

AX1 is the first implementation, focused exclusively on SOL.

---

## What is AX1

AX1 allows users to lock SOL as collateral and receive AX liquidity
without exposure to forced liquidation due to market volatility.

Key idea:
> Liquidity without liquidations.  
> No price oracles. No governance. Mandatory finalization.

---

## How AX1 Works

1. User deposits SOL into the protocol
2. AX is minted with fixed LTV (90%)
3. User uses AX freely
4. Position is finalized in one of two ways:
   - Voluntary redeem by the user
   - Automatic buyback and burn by the protocol

Every position **must** be finalized.

---

## Core Principles

- No price oracles
- No price-based liquidations
- Immutable rules
- Mandatory position finalization
- Buyback & burn as the only settlement mechanism

---

## AX1 Core Spec v0.1 (RU)

AX1 — это протокол залоговой ликвидности под SOL без ликвидаций по цене.

Ключевые свойства:
- Залог: SOL
- LTV: 90%
- Комиссия только по времени
- Отсутствие цен и оракулов
- Обязательный финал каждой позиции

Полная спецификация описывает:
- mint / redeem
- auto-buyback
- ограничения выпуска
- экономические инварианты

---

## AX1 Core Spec v0.1 (EN)

AX1 is a SOL-collateralized liquidity protocol with no price-based liquidations.

Key properties:
- Collateral: SOL
- LTV: 90%
- Time-based fee only
- No price oracles
- Mandatory position finalization

The full specification defines:
- mint / redeem
- auto-buyback
- issuance throttling
- economic invariants

---

## AXP (Pre-Token)

AXP is a pre-token used to mark early participation in the AX project.

AXP:
- is NOT part of AX1 protocol
- provides NO profit rights
- has NO guaranteed conversion
- does NOT affect protocol economics

AXP exists only as a participation marker.

---

## Project Status

- AX1 Core Spec v0.1 — completed
- Public documentation — live
- Development — upcoming
- Testnet — not launched yet

---

## Disclaimer

AX is an experimental protocol.
Nothing here constitutes financial advice.
Use at your own risk.
