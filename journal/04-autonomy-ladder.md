\# Autonomy ladder: three Acme tasks



| Task              | Level            | Why                  | Guardrails                      | Eval                         |

|-------------------|------------------|----------------------|---------------------------------|------------------------------|

| Policy question   | LLM app + RAG    | Read-only, low risk  | Approved docs only, cite source | Accuracy on known Q\&A set    |

| Ticket triage     | Agentic workflow | Repetitive, fixable  | Fixed categories, human if unsure | Routing accuracy vs past tickets |

| Payments incident | Human approval   | Money, hard to undo  | Read-only, human approves, audit log | Engineer review, zero unapproved actions |

