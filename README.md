# eca=Edge Context Attention
Project Goal: Edge Context Attention

Edge Context Attention (ECA) aims to build a local intelligence layer that helps enterprise AI systems understand business context before sending information to a large language model.

Instead of sending all enterprise data directly to a cloud-based LLM, ECA runs on the enterprise side and identifies the most relevant business objects, events, rules, and historical signals related to a specific problem.

Its goal is to transform scattered local data into a compact, structured, and high-quality problem context.

For example, when a user asks whether an order has delivery risk, ECA does not simply search for similar documents. It analyzes local business signals such as order status, material availability, supplier delay, production schedule, customer priority, and historical exceptions. Then it assigns relevance weights to these signals and generates a structured context for the Agent or LLM to reason over.

In short:

RAG retrieves relevant documents.
Edge Context Attention identifies relevant business context.

The core goal of ECA is to make enterprise AI systems more accurate, private, cost-efficient, and business-aware by moving context construction closer to the data source.

A more formal version:

Edge Context Attention is an edge-side context construction mechanism that dynamically attends to local business data, object relationships, events, rules, and historical states, producing structured problem context for Agents and LLMs. Its goal is to enable more accurate business reasoning without exposing unnecessary enterprise data to external models.

You can also describe it as:

ECA is the context intelligence layer between enterprise data and large language models. It helps the system decide what information matters before asking the model to reason.
