[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[<img align="right" width="150" src="https://firstcontributions.github.io/assets/Readme/join-slack-team.png">](https://join.slack.com/t/firstcontributors/shared_invite/enQtNjkxNzQwNzA2MTMwLTVhMWJjNjg2ODRlNWZhNjIzYjgwNDIyZWYwZjhjYTQ4OTBjMWM0MmFhZDUxNzBiYzczMGNiYzcxNjkzZDZlMDM)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/roshanjossey/first-contributions/badges/users.svg)](https://www.codetriage.com/roshanjossey/first-contributions)

# Перший внесок

Це важко. Це завжди важко - робити щось вперше. Проте якщо ви працюєте над проєктом з кимось, помилки будуть вдвічі неприємнішими. Але Open Source завжди пов’язаний з колективною роботою. Ми хочемо полегшити шлях для початківців, які бажають зробити свій перший внесок.

Можна прочитати безліч інструкцій та переглянути сотні відео, але що може бути краще, ніж спробувати зробити внесок не боючись нічого зламати? Ціль цього проєкту - надати можливість новачкам зробити їх перший внесок. Запам’ятайте: чим більше ви розслаблені, тим краще ви вчитеся. Якщо ви хочете зробити свій перший внесок, просто виконуйсте прості кроки нижче. Ми обіцяємо, що це буде весело!

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

Якщо ви ще не встановили GIT, тоді [ зробіть це негайно ]( https://help.github.com/articles/set-up-git/ ) :)

## Відгалужте репозиторій

Відгалужте свою власну копію цього репозиторія, натиснувши кнопку `fork` зверху цієї сторінки.
Таким чином, ви створите копію цього репозиторія у вашому акаунті.

## Клонуйте репозиторій

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Тепер клонуйте цей репозиторій на ваш комп’ютер. Натисніть на кнопку `clone`, а потім - на іконку `copy to clipboard`.

Відкрийте термінал і виконайте наступні команди:

```
git clone "посилання, яке ви щойно скопіювали"
```
де `посилання, яке ви щойно скопіювали` (без кавичок) - адреса цього репозиторію. Дивіться попередній крок для того, щоб отримати цю адресу.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

Наприклад:
```
git clone https://github.com/this-is-you/first-contributions.git
```
де `this-is-you` - ваш GitHub нікнейм. Таким чином, ви копіюєте вміст репозиторію з GitHub, в який збираєтесь зробити внесок, на ваш комп’ютер.

## Створюємо гілку

Перейдіть в директорію з репозиторієм на вашому комп’ютері (якщо ви ще цього не зробили):

```
cd first-contributions
```
Тепер створюємо гілку за допомогою команди `git checkout`:
```
git checkout -b <add-your-name>
```

Наприклад:
```
git checkout -b add-petro-church
```
(Назва гілки не повинна обов’язково містити слово *add*, але це має сенс, якщо майбутні зміни передбачають додавання чогось, наприклад, вашого імені у список контрибуторів.)

## Робимо необхідні зміни та записуємо їх в репозиторій

Тепер відкриваємо файл `Contributors.md` в текстовому редакторі і додаємо ваше ім’я, а потім зберігаємо файл. Якщо ви перейдете в директорію проєкту і виконаєте команду `git status`, ви побачите зміни. Додайте ці зміни до гілки, яку ви тільки що створили, за допомогою команди `git add`:
```
git add Contributors.md
```

Тепер запишіть ці зміни за допомогою команди `git commit`:
```
git commit -m "Add <your-name> to Contributors list"
```
замініть `<your-name>` своїм іменем.

## Відправляємо зміни в GitHub

Відправте зміни на віддалений репозиторій в GitHub за допомогою команди `git push`:
```
git push origin <add-your-name>
```
замініть `<add-your-name>` назвою гілки, яку ви створили раніше.

## Відправляємо зміни на перевірку

Коли ви перейдете до свого репозиторія в GitHub, ви побачите кнопку `Compare & pull request`. Сміливо натисніть на неї.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Тепер зміни відправлені на перевірку і затвердження.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Скоро я об’єднаю ваші запропоновані зміни з основною гілкою цього репозиторія. Ви отримаєте листа, коли це буде зроблено.

Основна гілка вашого репозиторія не буде змінена. Якщо ви хочете синхронізувати ваше відгалуження з моїм репозиторієм, слідуйте цієї інструкції.

## Зберігаємо свій репозиторій синхронізованим

 Спочатку перейдіть на основну гілку.
 ```
 git checkout master
 ```

 Потім додайте мій репозиторій як `upstream remote url`:
```
git remote add upstream https://github.com/Roshanjossey/first-contributions
```
Таким чином ми повідомляємо git про те, що інша версія цього проєкту існує за визначеною адресою і ми називаєм це  `upstream`. Як тільки зміни будуть об’єднані, заберіть нову версію мого репозиторію:
```
git fetch upstream
```
Тобто ви забираєте всі зміни з мого репозиторію. Тепер ви повинні об’єднати зміни, які прийшли з мого репозиторію, в вашу основну гілку.
```
git rebase upstream/master
```
Цим ви приймаєте всі зміни до основної гілки. Якщо ви відправите зміни до GitHub, ваше відгалуження також буде містити ці зміни:
```
git push origin master
```
Зауважте, що ви відправляєте зміни до віддаленого репозиторія, який був названий `origin`.

Тепер я об’єднав вашу гілку `<add-your-name>` з моєю основною гілкою, а ви об’єднали мою основну гілку зі своєю основною гілкою. Гілка, яку ви створювали для внесення змін, більше не потрібна. Ви можете видалити її:
```
git branch -d <add-your-name>
```
До того ж, ви можете видалити і її віддалену версію:
```
git push origin --delete <add-your-name>
```
Називати гілку в такий спосіб не обов’язково, однак це було зроблено з певною метою, аби показати призначення цієї гілки. Існування будь-якої гілки може бути коротким, адже врешті-решт, всі гілки об’єднуються з основною гілкою.

## Інструкції для інших інструментів

| <a href="gui-tool-tutorials/github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a> | <a href="gui-tool-tutorials/gitkraken-tutorial.md"><img alt="GitKraken" src="https://camo.githubusercontent.com/3793fd7afab1e383a841a5e39c681c802cdcbbb1ffa01571a06b1a167e086512/68747470733a2f2f6669727374636f6e747269627574696f6e732e6769746875622e696f2f6173736574732f6775692d746f6f6c2d7475746f7269616c732f6769746b72616b656e2d7475746f7269616c2f676b2d69636f6e2e706e67" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a> | <a href="gui-tool-tutorials/sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> | <a href="gui-tool-tutorials/github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/9/9c/IntelliJ_IDEA_Icon.svg" width=100></a> |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [GitHub Desktop](gui-tool-tutorials/github-desktop-tutorial.md)                                                                                             | [Visual Studio 2017](gui-tool-tutorials/github-windows-vs2017-tutorial.md)                                                                                                                          | [GitKraken](gui-tool-tutorials/gitkraken-tutorial.md)                                                               | [Visual Studio Code](gui-tool-tutorials/github-windows-vs-code-tutorial.md)                                                                                                                  | [Atlassian Sourcetree](gui-tool-tutorials/sourcetree-macos-tutorial.md)                                                                                                                                      | [IntelliJ IDEA](gui-tool-tutorials/github-windows-intellij-tutorial.md)                                                                                                                   |

## Що далі?

Ви можете приєднатися до нашої команди в Slack, якщо ви потребуєте будь-якої допомоги або маєте якісь запитання. [Приєднатися до команди в Slack](https://join.slack.com/t/firstcontributors/shared_invite/enQtMzE1MTYwNzI3ODQ0LTZiMDA2OGI2NTYyNjM1MTFiNTc4YTRhZTg4OWZjMzA0ZWZmY2UxYzVkMzI1ZmVmOWI4ODdkZWQwNTM2NDVmNjY)
