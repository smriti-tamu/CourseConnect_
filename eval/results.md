Evaluated on 20 labeled queries (142 relevant judgments).

| Mode | P@5 | R@10 | MRR@10 | nDCG@10 | ms/query |
|---|---|---|---|---|---|
| legacy | 0.710 | 0.781 | 0.900 | 0.798 | 32 |
| dense | 0.720 | 0.763 | 0.967 | 0.815 | 13 |
| bm25 | 0.550 | 0.573 | 0.880 | 0.651 | 16 |
| hybrid | 0.660 | 0.758 | 0.956 | 0.801 | 16 |
| hybrid_rerank | 0.680 | 0.699 | 1.000 | 0.777 | 152 |
