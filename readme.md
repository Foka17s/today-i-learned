Hallo World
-
УРОК 1.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Cd - перехід в директорію 

Cd (пробіл) .. - переміщення вгору в іншу директорію.

Ls - вивід списку файлів 

La -a - показ всіх директорій і файлів в поточній директорії 

Touch “touch foo.txt” - команда touch відповідає за створення нових файлів будь яких форматів в конкретній директорії

Mkdir “bar” - команда яка дозволяє створити директорію mkdir

Cp (copy)- копія будь якого файлу «cp foo.txt bar txt». Cp може вибирати розташування файлу копії “cp ./foo.txt (скопіювати і перейменувати за інш розташ.) ./bar-2.txt

Mv (move)- перенесення (на директорію вище наприклад) «mv foo.txt (на рівень вище і з іншою назвою, дві крапки пілся пробілу)  ../foo-3.txt

Cat - подивитись що є у файлі «cat first-file.rtf” (наприклад текст, код…)
Ця команда показує редагований вміст тексту чи будь чого, викликом її в консолі.

*ЦЕ ВСІ КОМАНДИ МЕНІ ЗНАДОБЛЯТЬСЯ, ЯКЩО В МЕНЕ НЕ БУДЕ ІНТЕРФЕЙСУ, ЯКЩО ФАЙЛ В КОГОСЬ НА КОМПІ АБО НА ГІТІ.

Сьогодні я вивчив такі команди для GIT BRUSH:
git commit - виконати, зберігти.
git checkout - контроль та перехід далі
git branch - створити гілку
git merge - злиття, об'єднання
git rebase - бере кіька комітів "копіює" їх, й кладе в інше місце
-
HEAD - це той коміт з яким ти зараз працюєш.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

git init - дати доступ гіту конкретної директорії до вашого гіта (онлайн)

*Перед командую “git init”, обов’язково потрібно виконати команду “git status”

git status - глянути доступ гіта до файла на компі в конкретній директорії.

*Червоні файли (антракт на інгліш) - це ті які не відслідковуються гітом зараз

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Основні розділі в Git:

1. Working Directory - робоча директорія (просто папка де ми редагуємо), з чого і де ваша робота починається і знаходиться в гіт.

2. Standing Area - все що знає гіт про нові створені файли, синхронізовані або не синхронізовані гітом.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
УРОК 2.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Команди в GIT BASH:

(уточнити) Git add - додати конкретно новий файл, зміни в ньому теж з моєї директорії в «оперативку» гіта (саме файл, не директорію). Тобто гіт відслідковує зміни у файлі. 

(уточнити) Можна також додати всі файли директорії  командою git add .

Git restore --staged foo.txt - команда яка дозволяє попросити гіт не слідувати за файлом.

*В директорії має бути доступ до гіта, цей доступ перевіряється наявністю папочки .git в директорії, її наявність можна перевірити знову ж командою «ls -a»

git commit -m (назва/короткий опис коміту) “second commit” - “git commit” це фіксація змін на гіті, тобто після додавання файлів в оперативку гіта ми фіксуємо їх в гіті вже остаточно, цк як збереження, знімок. Там буде перелік доданих до гіта файлів і інфа про них (скілкьи файлів попало в коміт, скільки видалено, скільки додано).
-m ставиться після git commit, для того шоб не описувати наш коміт довго в окремому файлі. Якщо після git commit поставити -m “name file” ввести git status, сам гіт мені скаже шо комітити нема чого, змін нема і покаже на якій гілці ми находимось.

Git log - показує всі коміти ти які я зробив де видно хеш. 
Хеш коміта - довга стрічка, яка відображає стан проєкту. Він динамічно міняється і допомагає мені знайти якийсь коміт, перейти на нього.

Шоб вийти з git log, треба натиснути клавішу Q.

Як дати доступ гітухабу до файлів/директорії:
git config user.name (ім'я користувача)
git config user.email (ел. пошта коритсувача)

Сьогодні я вивчив як робити Pull Request та декілька команд в Git Bash наведених вище.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Урок 3.




