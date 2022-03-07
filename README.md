# Lightweight Spanish Language Models

# Pre-trained models

| Model          | Parameters | Evaluation Average | Size  | Performance |
|----------------|------------|--------------------|-------|-------------|
| [BETO uncased](https://huggingface.co/dccuchile/bert-base-spanish-wwm-uncased)   | 110M       | -                  | 1x    | -           |
| [BETO cased](https://huggingface.co/dccuchile/bert-base-spanish-wwm-cased)     | 110M       | -                  | 1x    | -           |
| [DistilBETO](https://huggingface.co/CenIA/distillbert-base-spanish-uncased)     | 67M        | -                  | 1.66x | -           |
| [ALBETO tiny](https://huggingface.co/CenIA/albert_tiny_spanish)    | 5M         | -                  | 22x   | -           |
| [ALBETO base](https://huggingface.co/CenIA/albert_base_spanish)    | 12M        | -                  | 9.16x | -           |
| [ALBETO large](https://huggingface.co/CenIA/albert_large_spanish)   | 18M        | -                  | 6.11x | -           |
| [ALBETO xlarge](https://huggingface.co/CenIA/albert_xlarge_spanish)  | 59M        | -                  | 1.86x | -           |
| [ALBETO xxlarge](https://huggingface.co/CenIA/albert_xxlarge_spanish) | 223M       | -                  | 0.49x | -           |

# Fine-tuned models

## POS / NER

|                | POS       | NER       |
|----------------|-----------|-----------|
| BETO uncased   | [97.70](https://huggingface.co/CenIA/bert-base-spanish-wwm-uncased-finetuned-pos)     | [83.76](https://huggingface.co/CenIA/bert-base-spanish-wwm-uncased-finetuned-ner)     |
| BETO cased     | [**98.84**](https://huggingface.co/CenIA/bert-base-spanish-wwm-cased-finetuned-pos) | [**88.24**](https://huggingface.co/CenIA/bert-base-spanish-wwm-cased-finetuned-ner) |
| DistilBETO     | [97.50](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-pos)     | [81.19](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-ner)     |
| ALBETO tiny    | [97.04](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-pos)     | [75.11](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-ner)     |
| ALBETO base    | [98.08](https://huggingface.co/CenIA/albert-base-spanish-finetuned-pos)     | [83.35](https://huggingface.co/CenIA/albert-base-spanish-finetuned-ner)     |
| ALBETO large   | [97.87](https://huggingface.co/CenIA/albert-large-spanish-finetuned-pos)     | [83.72](https://huggingface.co/CenIA/albert-large-spanish-finetuned-ner)     |
| ALBETO xlarge  | [98.06](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-pos)     | [82.30](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-ner)     |
| ALBETO xxlarge | [98.35](https://huggingface.co/CenIA/albert-xxlarge-spanish-finetuned-pos)     | [84.36](https://huggingface.co/CenIA/albert-xxlarge-spanish-finetuned-ner)     |


## MLDoc / PAWS-X / XNLI

|                | MLDoc     | PAWS-X    | XNLI      |
|----------------|-----------|-----------|-----------|
| BETO uncased   | [96.38](https://huggingface.co/CenIA/bert-base-spanish-wwm-uncased-finetuned-mldoc)     | [84.25](https://huggingface.co/CenIA/bert-base-spanish-wwm-uncased-finetuned-pawsx)     | [77.76](https://huggingface.co/CenIA/bert-base-spanish-wwm-uncased-finetuned-xnli)     |
| BETO cased     | [96.65](https://huggingface.co/CenIA/bert-base-spanish-wwm-cased-finetuned-mldoc)     | [89.80](https://huggingface.co/CenIA/bert-base-spanish-wwm-cased-finetuned-pawsx)     | [81.98](https://huggingface.co/CenIA/bert-base-spanish-wwm-cased-finetuned-xnli)     |
| DistilBETO     | [96.35](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-mldoc)     | [75.80](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-pawsx)     | [76.59](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-xnli)     |
| ALBETO tiny    | [95.82](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-mldoc)     | [80.20](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-pawsx)     | [73.43](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-xnli)     |
| ALBETO base    | [96.07](https://huggingface.co/CenIA/albert-base-spanish-finetuned-mldoc)     | [87.95](https://huggingface.co/CenIA/albert-base-spanish-finetuned-pawsx)     | [79.88](https://huggingface.co/CenIA/albert-base-spanish-finetuned-xnli)     |
| ALBETO large   | [92.22](https://huggingface.co/CenIA/albert-large-spanish-finetuned-mldoc)     | [86.05](https://huggingface.co/CenIA/albert-large-spanish-finetuned-pawsx)     | [78.94](https://huggingface.co/CenIA/albert-large-spanish-finetuned-xnli)     |
| ALBETO xlarge  | [95.70](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-mldoc)     | [89.05](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-pawsx)     | [81.68](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-xnli)     |
| ALBETO xxlarge | [**96.85**](https://huggingface.co/CenIA/albert-xxlarge-spanish-finetuned-mldoc) | [**89.85**](https://huggingface.co/CenIA/albert-xxlarge-spanish-finetuned-pawsx) | [**82.42**](https://huggingface.co/CenIA/albert-xxlarge-spanish-finetuned-xnli) |

## QA

|                | MLQA, MLQA | TAR, XQuAD | TAR, MLQA |
|----------------|------------|------------|-----------|
| BETO uncased   | [- / -](https://huggingface.co/CenIA/bert-base-spanish-wwm-uncased-finetuned-qa-mlqa)      | - / -      | - / -     |
| BETO cased     | [- / -](https://huggingface.co/CenIA/bert-base-spanish-wwm-cased-finetuned-qa-mlqa)      | - / -      | - / -     |
| DistilBETO     | [- / -](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-qa-mlqa)      | - / -      | [- / -](https://huggingface.co/CenIA/distillbert-base-spanish-uncased-finetuned-qa-tar-mlqa)     |
| ALBETO tiny    | [- / -](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-qa-mlqa)      | - / -      | [- / -](https://huggingface.co/CenIA/albert-tiny-spanish-finetuned-qa-tar-mlqa)     |
| ALBETO base    | [- / -](https://huggingface.co/CenIA/albert-base-spanish-finetuned-qa-mlqa)      | - / -      | [- / -](https://huggingface.co/CenIA/albert-base-spanish-finetuned-qa-tar-mlqa)     |
| ALBETO large   | [- / -](https://huggingface.co/CenIA/albert-large-spanish-finetuned-qa-mlqa)      | - / -      | [- / -](https://huggingface.co/CenIA/albert-large-spanish-finetuned-qa-tar-mlqa)     |
| ALBETO xlarge  | [- / -](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-qa-mlqa)      | - / -      | [- / -](https://huggingface.co/CenIA/albert-xlarge-spanish-finetuned-qa-tar-mlqa)     |
| ALBETO xxlarge | [- / -](https://huggingface.co/CenIA/albert-xxlarge-spanish-finetuned-qa-mlqa)      | - / -      | - / -     |
