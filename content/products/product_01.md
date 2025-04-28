---
title: "queryApl"
accessible: false
order: 1
name: "queryApl"
category: "mcp-server-axiom-js"
path: "/service/design"
description: "Analyze Axiom datasets using Axiom Processing Language (APL) to filter, aggregate, and extract insights. Focus on optimizing queries by reducing time ranges, selective projections, and using aggregations for efficient data processing."
instructions:
  - "Analyze and solve complex problems by breaking them into adaptable steps. Recommends MCP tools for each stage, providing rationale and execution order to maintain context and filter irrelevant information."
  - "Query Axiom datasets using Axiom Processing Language (APL). The query must be a valid APL query string."
  - "ALWAYS get the schema of the dataset before running queries rather than guessing."
  - "Keep in mind that there's a maximum row limit of 65000 rows per query."
  - "Prefer aggregations over non aggregating queries when possible to reduce the amount of data returned."
  - "Be selective in what you project in each query (unless otherwise needed, like for discovering the schema). It's expensive to project all fields."
  - "NEVER guess the schema of the dataset. If you don't where something is, use search first to find in which fields it appears."
basic:
  - "Analyze and solve complex problems by breaking them into adaptable steps. Recommends MCP tools for each stage, providing rationale and execution order to maintain context and filter irrelevant information."
  - "Query Axiom datasets using Axiom Processing Language (APL). The query must be a valid APL query string."
  - "ALWAYS get the schema of the dataset before running queries rather than guessing."
  - "Keep in mind that there's a maximum row limit of 65000 rows per query."

header_class: "header-bg-transparent"
---
