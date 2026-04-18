# Sample Ontology Pattern

## Purpose

This file shows an abstracted pattern for building a domain-specific legal ontology.

It is intentionally simplified and does not disclose the full ontology used in live or confidential work.

---

## Pattern

### Step 1: Identify the legal unit
Determine the smallest meaningful legal concept.

Examples:
- party
- obligation
- approval
- filing step
- transfer restriction

### Step 2: Assign a node type
Each concept should belong to a controlled type.

Examples:
- Entity
- Financial Term
- Condition
- Procedure
- Rights/Obligations
- Risk Allocation

### Step 3: Attach source evidence
Each node should trace back to:
- source clause
- source page or section
- supporting text

### Step 4: Define relationships
Each node should connect to other nodes through controlled relationship verbs.

Examples:
- binds_to
- depends_on
- requires
- assigns
- triggers
- limits

### Step 5: Apply validation
Check:
- completeness
- relationship integrity
- evidence traceability
- critical dependency coverage

---

## Principle

A legal ontology should not be built as a static list.

It should be built as a controlled, evidence-backed structure that can support validation and workflow reuse.
