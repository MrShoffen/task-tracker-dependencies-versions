## Проект с версиями зависимостей

## Планировщик задач

Данный репозиторий предоставляет конфигурацию версий всех используемых зависимостей для согласованности между микросервисами.

Все зависимости расписаны в ibs.versions.toml - с помощью Gradle проект собирается в Version Catalog.
Остальные проекты, используя Github Packages, получают данный каталог и используют версии из него.