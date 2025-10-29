# FlowPost

**FlowPost** — локальная AI-платформа для автоматического создания, редактирования и публикации контента.

### 🚀 Основная идея
От голосового сообщения в Telegram до готового поста в Telegram, Dzen, Medium и Substack.

### ⚙️ Архитектура
- **Whisper** — распознавание речи
- **Llama-RU / Llama-EN** — генерация и адаптация текстов
- **Publisher** — публикации и обратная связь
- **FastAPI Hub** — логика пайплайна
- **Redis** — очереди и состояние

### 🧠 В планах
- Fine-tuning под стиль автора
- Stable Diffusion / Video Diffusion модули
- Веб-панель (SmartAdmin UI)
- Поддержка N8N как визуального оркестратора

---

## 🔧 Установка
```bash
git clone https://github.com/akurach/flowpost.git
cd flowpost
docker compose up --build
