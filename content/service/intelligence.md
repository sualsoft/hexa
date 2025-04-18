---
title: "Intelligence service page"
accessible: false
order: 5
name: "geminithinking"
path: "/service/intelligence"
category: "mcp-server-axiom-js"
description: "Analyze and solve complex problems by breaking them into adaptable steps. Recommends MCP tools for each stage, providing rationale and execution order to maintain context and filter irrelevant information."
stacks:
  - "Analyze and solve complex problems by breaking them into adaptable steps. Recommends MCP tools for each stage, providing rationale and execution order to maintain context and filter irrelevant information."
  - "Query Axiom datasets using Axiom Processing Language (APL). The query must be a valid APL query string."
  - "ALWAYS get the schema of the dataset before running queries rather than guessing."
  - "Keep in mind that there's a maximum row limit of 65000 rows per query."
  - "Prefer aggregations over non aggregating queries when possible to reduce the amount of data returned."
  - "Be selective in what you project in each query (unless otherwise needed, like for discovering the schema). It's expensive to project all fields."
  - "NEVER guess the schema of the dataset. If you don't where something is, use search first to find in which fields it appears."
header_class: "header-bg-transparent"
---
