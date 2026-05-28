# История решений

## 2026-05-28: Выбор стека

### Память агента
**Решение:** claude-mem (thedotmack) + локальные md-файлы  
**Почему:** Apache 2.0, бесплатно, работает с Claude SDK. Локальные файлы — резерв.  
**Отказались от:** Notion (платный), Mem.ai (платный Pro)

### База знаний
**Решение:** Anytype (anyproto/anytype-ts)  
**Почему:** Зашифрованный, локальный, P2P. Полная замена Notion бесплатно.  
**Отказались от:** Notion, Obsidian (ограниченный sync)

### Автоматизация
**Решение:** n8n self-hosted  
**Почему:** 400+ интеграций, AI-ноды, fair-code (можно для себя бесплатно)  
**Отказались от:** Zapier (дорого), Make (ограниченный free tier)

### Домен
**Решение:** .us.kg или .dpdns.org через DigitalPlat  
**Почему:** Бесплатно, 500k+ уже выдано, надёжный сервис  
**Деплой:** Cloudflare Pages (бесплатно) + Cloudflare Access (бесплатно для 1 пользователя)

### Браузер-автоматизация
**Решение:** playwright-mcp (microsoft/playwright-mcp)  
**Почему:** Официальный MCP Microsoft, deterministic, Apache 2.0. Лучше чем скриншоты.  
**Доп:** Claude in Chrome для Telegram Web

### Агентные плагины
**Решение:** anthropics/knowledge-work-plugins (11 плагинов)  
**Почему:** Официальные плагины Anthropic, бесплатно, MIT  
**Приоритет:** productivity → data → marketing → sales

---
_Обновлено: 2026-05-28_
