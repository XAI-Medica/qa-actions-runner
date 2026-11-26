
# XAI-Medica QA Actions Orchestrator (Public)

Публічний репозиторій-оркестратор для виконання GitHub Actions з метою економії лімітів хвилин приватних репозиторіїв.

## Призначення та безпека
* У цьому репозиторії **не зберігаються** вихідні коди продуктів, бінарні збірки або артефакти тестування.
* Workflow приймає подію `repository_dispatch` (`create_qa_issue`) та через секрет `QA_PRIVATE_REPO_TOKEN` створює картку `[QA]` у приватному репозиторії `XAI-Medica/qa-testing-log`.
