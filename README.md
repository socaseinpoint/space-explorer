# Space Explorer - A/B Testing

Космический туннель с двумя вариантами для A/B тестирования.

## Структура проекта

- **main** - основная ветка
- **variant-a** - Вариант A: Cyberpunk Tunnel (синие неоновые кольца)
- **variant-b** - Вариант B: Wormhole (фиолетовая червоточина с искажениями)

## Процесс разработки

Для каждой новой итерации:

1. Создаем изменения в обоих ветках
2. Push в GitHub
3. Vercel автоматически деплоит оба варианта

## Live URLs

После настройки Vercel:
- Variant A: `https://space-explorer-variant-a.vercel.app`
- Variant B: `https://space-explorer-variant-b.vercel.app`

## Локальный запуск

```bash
# Вариант A
git checkout variant-a
python3 -m http.server 8000

# Вариант B
git checkout variant-b
python3 -m http.server 8001
```
