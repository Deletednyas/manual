# Базовые команды для начала работы с GIT

**Перемещение по директории**
```
cd 
```
**Создание папки**
```
mkdir 
```
**Создание файла**
```
touch
```
**Удаление файла, рекурсивно, без подтверждения**
```
rm -rf
```
**Подключение GIT**
```
git init
```
**Синхронизация локального и удаленного репозитория**
```
git remote add origin git@github.com:login/project
```
**Добавление файлов в GIT (Важно находиться в папке с файлами)**
```
git add --all
```
**Сохранение проекта для дальнейшей публикации**
```
git commit -m 'Комментарий'
```
**Публикация в удаленный репозиторий**
```
git push
```
**Хеш — основной идентификатор коммита**


- Git преобразует информацию о коммитах с помощью алгоритма SHA-1 и для каждого из них рассчитывает уникальный идентификатор — хеш.
- Хеш — основной идентификатор коммита и позволяет узнать его автора, дату и содержимое закоммиченных файлов.
- Все хеши, а также таблицу соответствий хеш → информация о коммите Git хранит в папке .git.