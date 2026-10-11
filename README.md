# SpecDelta

SpecDelta is a standalone GenLayer specification-diff primitive. It compares two full commit-pinned specification documents, independently fetched by leader and validators. The nondeterministic extraction must return exact, source-anchored added and removed obligations, sorted and bounded. Consensus stores the delta with both source commitments. It has no owner, graph, certificate, settlement, allocation, or one-time consumption workflow.
