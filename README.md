# L2s

When looking at an L2, there are 3 important criterias:
1) Data Aspect
2) Sequencing Layer
3) Virtual Machine

## Data Aspect

1) Data is held onchain --> Rollup
2) Data is held offchain --> Validium

## Sequencing Layer

How is the ordering of transactions done?

1) Centralized Sequencer
2) Shared sequencer for cluster of L2s (superchain, ZKSync ecosystem...)
3) Based Sequencing --> uses the L1 for sequencing

## Virtual Machine (Execution)

1) Exactly EVM equivalent, where L2s use a precompile (ethereum exposing the EVM to the application layer through this precompile) --> Native Rollup
2) Different virtual machine than the exact copy of the EVM --> Custom Rollup

