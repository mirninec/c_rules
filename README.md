# c_rules
rules for c mudules

## Правила создания новых модулей в языке программирования Си.

#### 1. Создание пустых файлов

Создайте пустые файлы `newmod.c` и `newmod.h`:
<pre>
```bash
touch newmod.c newmod.h
```
</pre>

####  2. Вставка директивы в newmod.c
Вставьте в файл ***newmod.c*** следующую директиву:

<pre>
```c
#include "newmod.h"
```
</pre>
####  3. Вставка директив в newmod.h
Вставьте в файл ***newmod.h*** следующие директивы, оставив между ними пустое пространство для содержимого заголовочного файла:
<pre>
```c
#ifndef NEWMOD_H_SENTRY
#define NEWMOD_H_SENTRY

#endif
```
</pre>
#### 4. Регистрация в системе контроля версий и системе сборки
Зарегистрируйте созданные файлы в вашей системе контроля версий (например, Git) и системе сборки (если используется). Используйте соответствующие команды:

<pre>
```bash
# Регистрация в Git
git add newmod.c newmod.h
git commit -m "Добавлены файлы newmod.c и newmod.h"

# Другие действия по необходимости...
```
</pre>
#### 5. Отражение в документации
Обновите документацию вашего проекта, чтобы отразить появление нового модуля. Включите описание нового модуля, его назначение, и, при необходимости, инструкции по его использованию.

### Примечание:
Убедитесь, что документация поддерживается в актуальном состоянии и соответствует изменениям в вашем проекте.
