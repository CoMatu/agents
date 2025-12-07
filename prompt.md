Используя подход по оркестрации мультиагентной разработки (/Users/matu1/AndroidStudioProjects/agents/01_orchestrator.md), 
выполни доработку /Users/matu1/AndroidStudioProjects/tonometr/docs/tasks/notif.md.

Описание проекта находится в папке /Users/matu1/AndroidStudioProjects/tonometr/docs
Описание неполное.

Промпты агентов с указанными в 01_orchestrator.md ролями находятся в agents (02*.md..09.md).
Агентов нужно вызывать shell-командами:
cursor-agent -f --model {модель} -p {промпт}
и дожидаться от них результатов.

Промпт следующего формата:
"{содержимое файла с ролью} {входные данные согласно описанию роли}"

Модель:
аналитик, архитектор, планировщик — opus-4.5  
ревьюеры ТЗ, архитектуры, плана, кода и разработчик — composer-1