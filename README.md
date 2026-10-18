# 🤖 RebAiAgents (RebirtxAiAgents / RAA)

[English](#english) | [Русский](#русский)

---

## English

**RebAiAgents (RAA)** is a powerful, autonomous local AI agent equipped with a sleek dark graphical user interface (GUI), built-in multi-language toggle (RU/EN), and persistent session-based context memory. 

Designed specifically to bypass cloud restrictions, **RAA** bridges the gap between local LLMs (via Ollama) and your Windows operating system. It translates your natural language requests into clean Python scripts, intercepts execution logs, and safely automates your PC workflow completely offline.

### ✨ Key Features
* **Full Windows Automation:** Dynamically creates folders/files, monitors system specifications, fetches process workloads, and controls external software natively.
* **Persistent Multi-Chat Memory:** Open isolated chat sessions where the agent retains context, remembering paths, code snippets, and instructions from previous turns.
* **Execution Safety Guardrail:** Never executes hidden code. **RAA** displays the generated code and prompts you via a secure popup dialog box before modifying anything on your PC.
* **Autonomous Self-Healing Loop:** If a generated script encounters an environmental or syntax error, the agent automatically captures the console traceback, passes it back to the LLM, and patches the bug on the next iteration.
* **Model-Agnostic Interface:** Easily swap between any model pulled to your local Ollama instance (e.g., `qwen2.5:7b`, `llama3`, `mistral`) straight from the GUI panel.

### 🚀 Quick Start & Installation
1. Ensure **Ollama** is running in the system tray with your preferred model loaded (e.g., `ollama run qwen2.5:7b`).
2. Navigate to the **Releases** tab on the right side of this repository.
3. Download the standalone installer: `AI_Agent_Setup.exe`.
4. Run the installer wizard, which will unpack the binary and automatically deploy a working **RebAiAgents** shortcut onto your Desktop.

---

## Русский

**RebAiAgents (RAA)** — это мощный автономный локальный ИИ-агент, оснащенный графическим интерфейсом (GUI) в темных тонах, встроенным переключателем языков (RU/EN) и независимой памятью контекста для каждой сессии.

Созданный для работы полностью в офлайн-режиме, **RAA** связывает локальные нейросети (через Ollama) с операционной системой Windows. Он переводит ваши текстовые команды на естественном языке в полноценные Python-скрипты, перехватывает системные логи и безопасно автоматизирует рутину на вашем ПК.

### ✨ Основные возможности
* **Глубокая автоматизация Windows:** Динамически создает файлы и папки, собирает детальные характеристики железа, управляет процессами и запускает внешние программы.
* **Раздельная память чатов:** Возможность открывать независимые вкладки (чаты), в которых агент безупречно помнит контекст: созданные ранее пути, структуры и ваши прошлые правки.
* **Безопасность выполнения (Guardrail):** Никаких скрытых действий. **RAA** выводит сгенерированный код на экран и запрашивает явное подтверждение (Да/Нет) через системное диалоговое окно перед запуском скрипта.
* **Автономный цикл самоисправления:** Если код падает с ошибкой в консоли Windows, агент перехватывает Traceback сбоя, отправляет его обратно в модель и выдает исправленный рабочий вариант на следующем шаге.
* **Универсальный переключатель моделей:** Позволяет мгновенно переключаться на любую установленную у вас модель из Ollama (`qwen2.5:7b`, `qwen2.5:1.5b` и др.) прямо во время диалога.

### 🚀 Быстрая установка и запуск
1. Убедитесь, что сервер **Ollama** запущен (иконка ламы в трее) с загруженной моделью (например, `ollama run qwen2.5:7b`).
2. Перейдите в раздел **Releases** (Релизы) в правой части этого репозитория.
3. Скачайте готовый пакет установки: `AI_Agent_Setup.exe`.
4. Пройдите простой мастер установки Inno Setup, который автоматически распакует файлы программы и создаст ярлык **RebAiAgents** с иконкой прямо на вашем Рабочем столе.
