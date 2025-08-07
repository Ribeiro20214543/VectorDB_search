# **Avaliação comparativa de bancos de dados vetorias com base nos critérios de seleção pré-definidos**


| Banco Vetorial  | I   | II  | III | IV  | V   | VI  | Conclusão | Justificativa de Exclusão    |
|-----------------|-----|-----|-----|-----|-----|-----|-----------|-----------------------------|
| Chroma          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| Weaviate        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| Qdrant          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| Faiss           | ✓   | X   | X   | X   | ✓   | ✓   | Excluir  | II, III, IV                 |
| Elasticsearch   | ✓   | X   | X   | ✓   | ✓   | ✓   | Excluir  | II, III                    |
| OpenSearch      | ✓   | X   | X   | ✓   | ✓   | ✓   | Excluir  | II, III                    |
| Pinecone        | ✓   | ✓   | ✓   | ✓   | X   | ✓   | Excluir  | V                           |
| Milvus          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| Redis (Vector)  | ✓   | X   | ✓   | ✓   | ✓   | ✓   | Excluir  | II                          |
| Pgvector        | ✓   | X   | X   | X   | ✓   | ✓   | Excluir  | II, III, IV                 |
| Marqo           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| Vespa           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| LanceDB         | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| Deep Lake       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | Incluir   |                             |
| MongoDB         | ✓   | X   | X   | ✓   | X   | ✓   | Excluir  | II, III, V                 |
| CockroachDB     | ✓   | X   | X   | X   | ✓   | ✓   | Excluir  | II, III, IV                |
| Cassandra       | ✓   | X   | X   | X   | ✓   | ✓   | Excluir  | II, III, IV                |
| Vectara         | ✓   | ✓   | ✓   | ✓   | X   | ✓   | Excluir  | V                           |
| Astra DB        | ✓   | X   | X   | X   | X   | ✓   | Excluir  | II, III, IV, V             |
| Upstash         | ✓   | X   | X   | X   | X   | ✓   | Excluir  | II, III, IV, V             |
| Zilliz          | ✓   | ✓   | ✓   | ✓   | X   | ✓   | Excluir  | V                           |

