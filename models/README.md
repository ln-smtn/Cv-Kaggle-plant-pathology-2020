# Веса моделей


| Файл | Описание |
|------|----------|
| `model_fold{0..4}.pth` | Stage 1: лучшие веса по validation AUC для каждого фолда. |
| `model_fold{0..4}_distill.pth` | Stage 2: дистилляция поверх Stage 1. |

**Инференс:** если есть `model_fold0_distill.pth`, подхватываются дистиллированные веса и веса ансамбля считаются по `distill_scores`, иначе — Stage 1 и `fold_scores`.


