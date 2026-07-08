# AMYO Enrichment Vault

**Purpose:** off-repo Markdown/Obsidian-compatible workspace for AMYO business discovery, research, idea development, tax/finance analysis, TruckMatch phasing, and promotion package preparation.

This repository exists because the main AMYO implementation repository must stay clean, governed, and approval-gated. Raw thinking, competing ideas, research notes, and AI collaboration happen here first.

## Current AMYO baseline

- Main repo: `AMYO-Business-Group/amyo-enterprise-os`
- Current baseline commit: `01c3f230768039b23b4b67960a9b115144719e7e`
- Supabase project: `qkgiphcldakisnqyaboo`
- Vercel project: `amyo-enterprise-os-web`
- Notion Command Center exists and includes the AMYO Business Enrichment Hub.
- Stage 1 browser smoke test passed.
- Supabase Security Advisor leaked-password warning cleared.
- TruckMatch Load Request lifecycle is approved for planning, not implementation.

## Source-of-truth hierarchy

1. Approved files in the main AMYO implementation repo.
2. Supabase hosted schema and runtime state.
3. Notion Command Center and Enrichment Hub structured records.
4. This vault's finalized promotion packages.
5. This vault's drafts and raw notes.
6. Chat discussions and AI-generated proposals.

This vault is **not** the production source of truth. It is a staging and synthesis workspace.

## Promotion pipeline

```text
Raw idea
→ Vault note
→ Structured vault analysis
→ Notion Enrichment Hub record
→ Approval gate
→ GitHub main repo issue/ADR/implementation plan
→ PR / migration / tests
→ Vercel/Supabase validation
→ Notion status sync
```

## Standing rules

- Do not treat AI output as verified fact.
- Do not treat tax/regulatory notes as legal truth until sourced.
- Do not promote Khat, Sesame, Avocado, or future boxes into runtime without ADR approval.
- Do not push raw ideas into the main repo.
- Do not add Supabase schema concepts from this vault without an approved implementation plan.
- Separate Now / Next / Later / Do Not Implement Yet.
- Every promoted item needs scope, non-goals, data impact, RLS impact, validation plan, and rollback notes.
