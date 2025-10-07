name: Баг
description: Неправильное поведение или падение
title: "[bug] "
labels: ["bug"]
body:
  - type: textarea
    id: what
    attributes:
      label: Что произошло
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Шаги воспроизведения
  - type: textarea
    id: logs
    attributes:
      label: Логи/скриншоты
