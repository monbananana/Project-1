# Project

## Dataset

This project uses the SciFact dataset, a public dataset designed for scientific claim verification.The retrieval corpus contains scientific research documents, including paper titles and abstracts. Each query represents a scientific claim. The retrieval task is to identify the document or documents that contain relevant evidence for the claim.

Dataset components:

- `queries.jsonl`: scientific claims used as search queries
- `corpus.jsonl`: scientific paper titles and abstracts
- `train.tsv`: query-document relevance pairs for training
- `test.tsv`: query-document relevance pairs for evaluation
