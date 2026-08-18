# Gold Shop Management

A lightweight, console-based inventory management and automated retail billing engine implemented in standard ANSI C. This software provides jewelry boutiques with an efficient operational terminal to track gold asset reserves, adjust dynamic valuation indices based on metal purity (karats), and instantly output structured consumer billing receipts featuring precise financial breakdowns.
## Core Features
Dynamic Market Matrix: Real-time interactive terminal updates for fluctuating 24K, 22K, and 18K raw gold market prices per gram.Comprehensive Inventory Ledger: Tracks complete asset metadata including unique identification keys, catalog categories, precise item weights, crafting/making charges, and localized stock depths.Automated Transaction Terminal: Features an integrated checkout workflow that validates stock availability, deducts sold quantities, computes raw commodity weights against structural purity rules, and incorporates a standard 5% VAT rate.Memory Buffer Guardrails: Implements clean loop-handling mechanisms and parsing input flushes to defend the system console against terminal string overflows or unexpected datatype evaluation failures.
## 🛠️ System Architecture & Data Models
The management system organizes local memory boundaries using structural struct record mappings to manage entities systematically.
**1. Market Value Mapping**
Stores current market valuation indices per gram for various purity categories:
