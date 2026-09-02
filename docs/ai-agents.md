# AI Marketing Stack — AI Agents

## Overview

The AI Marketing Stack uses specialized AI agents to support different parts of the marketing process.

The agents are designed to have clearly defined roles rather than attempting to make one general-purpose assistant responsible for everything.

This makes it possible to develop, test and improve individual capabilities while gradually connecting them into a broader ecosystem.

## Agent Ecosystem

The current architecture includes capabilities for:

- Competitive intelligence
- Market intelligence
- Marketing strategy
- Content marketing
- Campaign analysis and learning

The agents can operate independently when appropriate, but the longer-term objective is to connect them so that information and insights can flow between capabilities.

```text
                    AI Marketing Stack

             ┌──────────────────────────┐
             │   Shared Marketing       │
             │   Context & Knowledge    │
             └────────────┬─────────────┘
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
        ▼                 ▼                 ▼
 Competitive          Market           Content
 Intelligence       Intelligence      Marketing
        │                 │                 │
        └────────────┬────┴─────────────────┘
                     │
                     ▼
               Market Strategy
                     │
                     ▼
              Campaign Activity
                     │
                     ▼
             Campaign Performance
                     │
                     ▼
              Campaign Learning
                     │
                     └──────────► Future Decisions
