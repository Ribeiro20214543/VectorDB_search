
# **QUADRO: Avaliação comparativa entre os modelos de embedding retornados na pesquisa realizada na plataforma Hugging Face**

| Nº | Modelo                                                          |  I  | II  | III | IV  |  V  | VI  | VII | VIII | IX  |  X  | XI  | XII | Conclusão | Justificativa de Exclusão               |
|----|------------------------------------------------------------------|-----|-----|-----|-----|-----|-----|-----|------|-----|-----|-----|-----|-----------|------------------------------------------|
| 1  | sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 2  | intfloat/multilingual-e5-small                                  | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 3  | intfloat/multilingual-e5-base                                   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 4  | Alibaba-NLP/gte-multilingual-base                               | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 5  | ibm-granite/granite-embedding-107m-multilingual                 | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 6  | sentence-transformers/LaBSE                                     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 7  | armand01/paraphrase-multilingual-MiniLM-L12-v2-Q6_K-GGUF        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 8  | sizrox/paraphrase-multilingual-mpnet-base-v2-Q8_0-GGUF          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 9  | ibm-granite/granite-embedding-278m-multilingual                 | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 10 | sentence-transformers/distiluse-base-multilingual-cased-v1      | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 11 | sentence-transformers/distiluse-base-multilingual-cased-v2      | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 12 | sentence-transformers/paraphrase-multilingual-mpnet-base-v2     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 13 | ef-zulla/e5-multi-sml-torch                                     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 14 | woody72/multilingual-e5-base                                    | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 15 | kev216/sentence-embedding-LaBSE                                 | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 16 | elastic/multilingual-e5-small-optimized                         | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI                                       |
| 17 | strauss-oak/mdl_bertopic_globo                                  | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 18 | hicustomer/paraphrase-multilingual-MiniLM-L12-v2                | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 19 | mlx-community/multilingual-e5-base-mlx                          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 20 | mlx-community/multilingual-e5-small-mlx                         | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 21 | maiyad/multilingual-e5-small                                    | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 22 | tomaarsen/distiluse-base-multilingual-cased-v2                  | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 23 | elastic/multilingual-e5-small                                   | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 24 | Griffin88/my_new_model3                                         | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 25 | Griffin88/sentence-embedding-LaBSE                              | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 26 | antoinelouis/dpr-xm                                             | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | VII, XII                                 |
| 27 | lang-uk/ukr-paraphrase-multilingual-mpnet-base                  | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 28 | beademiguelperez/sentence-transformers-multilingual-e5-small    | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 29 | DmitryML/distiluse-base-multilingual-cased-v1                   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, XII                              |
| 30 | 0xnu/pmmlv2-fine-tuned-yoruba                                   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, XII                              |
| 31 | 0xnu/pmmlv2-fine-tuned-igbo                                     | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, XII                              |
| 32 | 0xnu/pmmlv2-fine-tuned-flemish                                  | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, XII                              |
| 33 | 0xnu/pmmlv2-fine-tuned-hausa                                    | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                       
| 34 | ChristianAzinn/labse-gguf                                       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VII                                      |
| 35 | sartifyllc/African-Cross-Lingua-Embeddings-Model                | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VII                                      |
| 36 | tomaarsen/xlm-roberta-base-multilingual-en-ar-fr-de-es-tr-it    | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, X                               |
| 37 | ammumadhu/kunato-indic-bert                                     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 38 | BookingCare/multilingual-e5-base-similarity-v1-onnx-quantized   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, X                               |
| 39 | OneFly7/biencoder_ep10_bs64_all                                 | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, X                               |
| 40 | upskyy/gte-base-korean                                          | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 41 | upskyy/bge-m3-korean                                          | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 42 | upskyy/e5-base-korean                                         | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 43 | upskyy/e5-small-korean                                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 44 | upskyy/e5-large-korean                                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 45 | mykor/paraphrase-multilingual-MiniLM-L12-v2                   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 46 | Jaume/gte-multilingual-base-no-network                        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 47 | Marqo/multilingual-e5-small                                   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 48 | leeloolee/intention                                           | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 49 | ganser4566/paraphrase-multilingual-MiniLM-L12-v2              | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 50 | OneFly7/biencoder_ep10_bs64_trans3                            | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 51 | OneFly7/biencoder_ep10_bs64_trans1                            | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 52 | OneFly7/crossencoder_ep10_bs8_trans1                          | ✓   | X   | X   | X   | ✓   | X   | X   | X    | X   | X   | ✓   | ✓   | Excluído  | II, III, IV, VI, VII, VIII, IX, X         |
| 53 | chukbert/paraphrase-multilingual-MiniLM-L12-v2-MSRP-Indo...   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VII                                      |
| 54 | ImranzamanML/multilingual-mpnet-finetuned                     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 55 | yixuan-chia/multilingual-e5-base-gguf                         | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 56 | BookingCare/multilingual-e5-base-v3-onnx-quantized            | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 57 | sentence-transformers/static-similarity-mrl-multilingual-v1   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Incluído  |                                          |
| 58 | artificial-nerds/pmnet                                        | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 59 | OneFly7/biencoder_ep10_bs32_trans3                            | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 60 | OneFly7/biencoder_ep2_bs32_trans3                             | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 61 | deepfile/multilingual-e5-small-openvino                       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 62 | deepfile/multilingual-e5-small-onnx-qint8                     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 63 | EnverLee/bge-m3-korean-Q4_K_M-GGUF                            | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | VI, VII, XII                             |
| 64 | OneFly7/bi_bs32_lr2e5_cosine_restart_period2_best             | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 65 | luanafelbarros/bert-es-pt-cased-matryoshka                    | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI                                       |
| 66 | vallabh001/xlm-roberta-base-multilingual-en-es                | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 67 | jncraton/multilingual-e5-small-ct2-int8                       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 68 | Maxthemacaque/onnx-gte-multilingual-base                      | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 69 | OneFly7/biencoder_ep10_bs32_lr2e5_cosine_annealing_hard_neg_1 | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 70 | OneFly7/biencoder_ep10_bs32_lr2e5_cosine_annealing_hard_neg_2 | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 71 | Naresh/multilingual-e5-base-Q4_K_M-GGUF                       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 72 | hongkeon/bge-m3-korean-Q8_0-GGUF                              | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | VI, VII, XII                             |
| 73 | hongkeon/e5-large-korean-Q8_0-GGUF                            | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | VI, VII, XII                             |
| 74 | dinab/multilingual-e5-base-Q4_K_M-GGUF                        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 75 | Nagase-Kotono/e5-large-korean-Q8_0-GGUF                       | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | VI, VII, XII                             |
| 76 | dinab/multilingual-e5-base-Q4_0-GGUF                          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 77 | dinab/multilingual-e5-base-Q8_0-GGUF                          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 78 | dinab/multilingual-e5-base-Q5_K_S-GGUF                        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 79 | dinab/multilingual-e5-base-Q4_K_S-GGUF                        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 80 | hongkeon/bge-m3-korean-Q4_K_M-GGUF                            | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | VI, VII, XII                             |
| 81  | onelevelstudio/M-E5-BASE                           | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 82  | onelevelstudio/M-MPNET-BASE                        | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 83  | cstr/paraphrase-multilingual-MiniLM-L12-v2-mlx     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 84  | onelevelstudio/MPNET-0.3B                          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 85  | onelevelstudio/ML-E5-0.3B                          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 86  | mradermacher/ML-E5-0.3B-GGUF                       | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 87  | ipetrukha/ukr-paraphrase-multilingual-mpnet-base   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VII                                      |
| 88  | shtilev/medical_embedded_v1                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | X   | Excluído  | VI, VII, X, XII                         |
| 89  | badger212/granite-embedding-278m-multilingual...   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 90  | shtilev/medical_embedded_v2                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | X   | Excluído  | VI, VII, X, XII                         |
| 91  | roytmana/paraphrase-multilingual-mpnet-base-v2...  | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 92  | matichon/multilingual-e5-base-Q4_K_M-GGUF          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 93  | thiagocmach/paraphrase-pt-bible                    | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI                                       |
| 94  | T3LS/static-similarity-mrl-multilingual-v1-32d...  | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 95  | shtilev/medical_embedded_v3                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | X   | Excluído  | VI, VII, X, XII                         |
| 96  | MintplexLabs/multilingual-e5-small                 | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 97  | janawajeeh/sbert_model4                            | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 98  | jirawan-chro/RAG-thai                              | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, X                               |
| 99  | podarok/ukr-paraphrase-multilingual-mpnet-base     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VII                                      |
| 100 | Moriec/Vinogradov_semantic_search                  | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 101 | ngkan146/MNLP_M2_document_encoder                  | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 102 | Smxldo/MNLP_M3_document_encoder                    | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 103 | jeremyys/multilingual-e5-base-Q5_0-GGUF            | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 104 | jeremyys/multilingual-e5-base-Q4_K_M-GGUF          | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 105 | mishutqac/paraphrase-multilingual-mpnet-base-v2    | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 106 | shtilev/medical_embedded_v4                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | X   | Excluído  | VI, VII, X, XII                         |
| 107 | tasal9/Multilingual-ZamAI-Embeddings               | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 108 | Hiveurban/multilingual-e5-base                     | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 109 | Dyna-99/local-st-model                             | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 110 | AzrilFahmiardi/persona-fit-embedding               | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 111 | shtilev/medical_embedded_v5                        | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, X                               |
| 112 | linhha2705/multilingual-e5-nutrition               | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | X   | ✓   | ✓   | Excluído  | VI, VII, X                               |
| 113 | oxygeneDev/paraphrase-multilingual                 | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 114 | Borsa356/NLI_MNRL_EN_                              | ✓   | ✓   | ✓   | ✓   | ✓   | X   | X   | ✓    | ✓   | ✓   | ✓   | ✓   | Excluído  | VI, VII                                  |
| 115 | pyarn/paraphrase-multilingual-mpnet-base-v2-Q8_0...| ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
| 116 | SzymonKozl/setfit-app-class-dm                      | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 117 | SzymonKozl/setfit-app-class-lidl                    | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 118 | SzymonKozl/setfit-app-class-rewe                    | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 119 | SzymonKozl/setfit-app-class-rossmann                | X   | X   | X   | X   | X   | X   | X   | X    | X   | X   | X   | ✓   | Excluído  | I, II, III, IV, V, VI, VII, VIII, IX, X, XI |
| 120 | soprasteria/gte-multilingual-base                   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓   | ✓    | ✓   | ✓   | ✓   | X   | Excluído  | XII                                      |
