# **Инструкция по работе с GIT**

LICENSE: [MIT](./lisence.md)

![git-logo](./git-logo.png)

---
**GIT** - распределенная система управления версиями.
Основная задача GIT - фиксиция различных изменений, произведенных с документами, и возможность отслеживать и управлять этими изменениями.


### **Установка Git для различных ОС:**
1. [Linux Ubuntu](./instal-Linux.md)
2. [MacOS](./instal-MacOS.md)
3. [Windows](./instal-Windows.md)
---
### **Основные операции:**
1. [git config](./config.md)
2. [git init](./init.md)
3. [git add](./add.md)
4. [git commit](./commit.md)
5. [git clone](./clone.md)
---
### **Работа с удалённым репозиторием**
<table>
  <tr>
    <th>Команда</th>
    <th>Свойство</th>
  </tr>
  <tr>
    <td> 
    <strong>git remote add [имя_удаленного_репозитория] [адрес] </strong> 
    </td>
    <td> Добавляет связанные удаленные репозитории.</td>
  </tr>
  <tr>
    <td> 
    <strong>git fetch</strong>
    </td>
    <td> Получение изменений с удаленного репозитория.</td>
  </tr>
  <tr>
    <td>
    <strong>git merge</strong>
    </td>
    <td>Слияние полученных изменений и локального репозитория.</td>
  </tr>
  <tr>
    <td>
    <strong>git pull</strong>
    </td>
    <td>Объединеняет две последовательные команды git fetch и git merge.</td>
  </tr>
  <tr>
    <td><strong>git push</strong></td>
    <td>Отправляет ваши изменения в репозиторий.</td>
  </tr>
</table>

---
### **Получение данных о состоянии репозитория**
```git status``` - отслеживание состояния репозитория.

```git log``` - показывает список последних коммитов и их хеши SHA1.

```git show [хэш]``` - показывает информацию по определённому коммиту.

---
## Файл .gitignore
Cуществуют файлы, которые нельзя добавлять в репозиторий. Такие файлы требуется добавлять в игнорируемые для **GIT**.
Файл с описанием файлов, для которых не должно вестись отслеживание версий, имеет расширение **.gitignore**. Файл **.gitignore** представляет собой текстовый файл с перечнем шаблонов файловых имён, которые не должны отслеживаться..

### [Основные правила синтаксиса для файла ***.gitignore***](./basic-syntax.md)

---

GIT logo by Jason Long- https://git-scm.com/downloads/logos, lisence: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)