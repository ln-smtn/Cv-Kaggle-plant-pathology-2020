# Логи обучения

| Путь | Назначение |
|------|------------|
| `history/training_log.csv` | Построчно: эпоха, фолд, stage (1 или 2), `train_loss`, `valid_auc`, `lr`. Пишется после Stage 1 и обновляется после Stage 2. |
| `history/training_log_full.csv` | Полный экспорт (если вы вручную копировали расширенный лог). |
| `reports/training_summary.txt` | Краткая сводка: AUC по фолдам, mean/std, лучший фолд, время. |
| `reports/training_log_best_fold.txt` | Заметки по лучшему фолду (если вели). |

В ноутбуке путь к основному CSV задаётся как `logs/history/training_log.csv`.
