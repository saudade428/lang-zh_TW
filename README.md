# lang-zh_TW

### 請在您準備翻譯前閱讀以下內容!

這個翻譯項目裡包含了16個txt文件, 分別對應Unraid系統中相應的部分:

- translations.txt -- 包含通用(general)翻譯, 每次都會載入
- helptext.txt     -- 包含所有幫助文本的翻譯 , 每次都會載入
- dashboard.txt    -- 包含儀錶板(dashboard)部分的翻譯
- main.txt         -- 包含主要部分的翻譯
- shares.txt       -- 包含共享部分的翻譯
- users.txt        -- 包含用戶部分的翻譯
- settings.txt     -- 包含設置部分的翻譯
- plugins.txt      -- 包含插件部分的翻譯
- docker.txt       -- 包含容器(docker)部分的翻譯
- vms.txt          -- 包含虛擬機部分的翻譯
- tools.txt        -- 包含工具部分的翻譯
- javascript.txt   -- 包含javascript腳本部分的翻譯
- scripts.txt      -- 包含本地腳本部分的翻譯
- apps.txt         -- 包含社區軟體(apps)部分的翻譯
- ca_settings      -- 包含社區軟體設置部分的翻譯
- javascript.ca.txt-- 社區軟體提供的javascript部分的翻譯

為保證翻譯完整性, 所有檔案名必須是小寫的, 並且所有文件都應該包含在倉庫中.

刪除掉某個文件，意味著該部分將沒有可用的翻譯，WEB GUI將顯示原始的英語文本.

### 翻譯

每個文本文件都包含以UTF-8格式儲存的常規文本字串, 並帶有linux行結束符.
應使用支持UTF-8和linux格式的文本編輯器, 例如 [notepad++](https://notepad-plus-plus.org/downloads)

每個文本文件的內容分為兩個部分

### 第一部分

具有固定格式的單行條目:

`原始的英語文本=翻譯後的文本`

只修改等號(=)後面的文本,不應修改左側的原始英文文本.
刪除一行或省略等號後面的翻譯, WEB GUI將會顯示這一行內容的原始英語文本.

翻譯後的文本可含有"特殊字元", 如斜槓, 圓括號或方括號, 這些字元原本不在原文中, 不過可被添加以按需補充說明性文字，使譯文易於理解. 
例如.
`Options see Help=選項 (查看幫助)`

使用 \* 字元標示內容, 可使得對應內容以斜體顯示,
使用 \*\* 字元標示內容, 可使得對應內容以粗體顯示.
例如.
`Array must be Stopped to change=如要更改設置, 磁碟陣列必須先**停止**`

建議分別翻譯各個部分, 即每次翻譯一個文件, 並在WEB GUI中驗證翻譯的正確性.

請盡可能匹配翻譯後文本與原文本的長度, 避免WEB GUI中顯示錯亂.

### 第二部分

用於一次性翻譯多行文本的條目.
多行翻譯條目有唯一的開始和結束標籤:

**:unique_tag_name_plug:** - 用於任何多行文本(unique_tag_name_plug)部分的唯一開始標籤

**:end**    - 多行翻譯條目的結束標籤

不要刪除或改變這些標籤, 只翻譯開始和結束標籤之間的文本!

### 幫助文本

WEB GUI所有的幫助文本都儲存在一個文件中 *helptext.txt*.

這個文件有包含多個部分的幫助文本. 每個部分都包含唯一的開始標籤和相應的結束標籤.

**:unique_tag_name_help:** - 幫助文本部分的唯一開始標籤

**:end**    - 相應的結束標籤

不要刪除或改變這些標籤, 只翻譯開始和結束標籤之間的文本!

注意: 使用了Markdown語法, 相關的格式描述符必須保留.

### 本地測試

翻譯完成後，如您希望在本地(臨時)測試結果, 需要將文本文件壓縮到單個ZIP文件中.
將ZIP文件命改為您翻譯的語言, 例如. zh_CN.zip.

在WEB GUI中如下設置: 工具 -> webGUI -> 語言 (切換到開發者視圖)

- 默認情況下, 只安裝英語語言(內建).
- 選擇翻譯後創建的ZIP文件.
- 如果系統識別出語言名稱, 將自動選擇語言名稱, 否則請在下拉菜單中選擇語言名稱進行安裝.
- 點擊"上傳", 您的翻譯會出現在WEB GUI語言選項的下拉菜單中.

提示: 如果下拉菜單中沒有列出您的語言, 請在論壇中提交回饋 [Unraid forum](https://forums.unraid.net/forum/75-multi-language-section/)

現在你可以對翻譯後的文本進行本地測試了!

在WEB GUI中如下設置: Settings -> Display Settings -> Language

- 從下拉菜單中選擇首選語言. (只有成功安裝語言才會出現在列表中)

### GITHUB

語言倉庫在 [Github](https://github.com/unraid) 上提供, 翻譯人員可以隨時創建PR(Pull Request)提交翻譯成果.

請使用Github(需要註冊帳戶)派生(fork)官方語言儲存庫到自己的帳戶, 一旦您翻譯完成, 就可以創建PR.

負責人 Limetech 將審查提交內容, 審查通過後會合併您的修改.

### 更新

當有新的英語文本可用時, 會在Github提供更新.

翻譯人員可以使用Github系統查看做出了哪些更改, 並相應地更新他們的翻譯.

### 致謝

我們非常歡迎您參與到翻譯工作中，為了表達我們的感激之情，您的名字和語言將被記錄到GUI工具頁面下的"致謝"(Credits)頁面。

非常感謝!


# lang-zh_TW

### READ THIS WHEN YOU WANT TO MAKE TRANSLATIONS TO ANOTHER LANGUAGE

There are sixteen text files included in this repository, each with their own section of translations:

- translations.txt -- these are general translations and loaded each time
- helptext.txt     -- these are all help text sections and loaded each time
- dashboard.txt    -- these are translations for the dashboard section
- main.txt         -- these are translations for the main section
- shares.txt       -- these are translations for the shares section
- users.txt        -- these are translations for the users section
- settings.txt     -- these are translations for the settings section
- plugins.txt      -- these are translations for the plugins section
- docker.txt       -- these are translations for the docker section
- vms.txt          -- these are translations for the vms section
- tools.txt        -- these are translations for the tools section
- javascript.txt   -- these are translations for javascript scripts
- scripts.txt      -- these are translations for local scripts
- apps.txt         -- these are translations for the CA section
- ca_settings      -- these are translations for the CA settings
- javascript.ca.txt-- these are translations for the CA javascript

All file names are in lowercase and should be included in the repository to make the translations complete.

Removing a particular file, means no translations will be available for that section and the GUI will display text in original English.

### TRANSLATIONS

Each text file contains regular text strings stored in UTF-8 format with linux line-endings.
Use a text editor which supports UTF-8 and linux format, like [notepad++](https://notepad-plus-plus.org/downloads)

The content of each text file is separated into two parts

### PART 1

These are single line entries which are in the format:

`original English text=translated Foreign text`

Only modify the text after the equal sign(=) and leave the original English text at the left untouched.
Removing a line or omitting a translation after the equal sign, results in the GUI displaying this line with the original English text.

The translated text may have 'special characters', such as slashes, parenthesis or brackets which are not included in the key text,
but which are used to display text accordingly. E.g.

`Options see Help=Options (see Help)`

The characters \* and \*\* are used to display text in italics and bold respectively. E.g.

`Array must be Stopped to change=Array must be **Stopped** to change`

It is recommended to make translations per section, that is one file at the time, and verify the correctness of the translations in the GUI
before proceeding with the next section.

Keep in mind the length of the translations and try to make them similar length as the original text and avoid space issues in the GUI.

### PART 2

These are multi line entries used to translate multiple lines at once.
Multi line translations have a unique opening and closing tag:

**:unique_tag_name_plug:** - unique opening tag used for any multi line text section

**:end**    - closing tag

Do not remove or alter these tags and only translate the text between the opening and closing tags!

### HELP TEXT

All help text of the GUI is stored in a single file *helptext.txt*.

This file has multiple help text sections. Each section is enclosed by a unique opening tag and corresponding closing tag.

**:unique_tag_name_help:** - unique opening tag used for a help text section

**:end**    - corresponding closing tag

Do not remove or alter these tags and only translate the text between the opening and closing tags!

Be aware that Markdown styling syntax is used, this must be preserved.

### LOCAL TESTING

Once the translations are complete and you want to test locally the (intermediate) results, the text files need to be zipped into a single ZIP file.
Give the ZIP file the name of your language, e.g. French.zip.

In the GUI go to: Tools -> webGUI -> Language (switch to Developer view)

- By default only the English language is installed (built-in)
- Choose the ZIP file you have created earlier as the source file
- If the language name is recognized, it will be automatically selected, otherwise chose the name of the language from the dropdown menu to install.
- Click on "Upload" will add your translations to the GUI under the selected language name

NOTE: If your language is not available from the dropdown menu, please make a request on the [Unraid forum](https://forums.unraid.net/forum/75-multi-language-section/)

Now your language is available for local testing!

In the GUI go to: Settings -> Display Settings -> Language

- Select the preferred language from the dropdown menu. Note that only the available language choices are displayed here.

### GITHUB

A language repository will be made available at [Github](https://github.com/unraid), where translators can create Pull Requests (PR) and submit their work.

Once you are satisfied with your results, use Github (an account is required) to fork the respective language repository and create a PR with your modifications.

Limetech will review this and merge your work when approved.

### UPDATES

When updated source text files in English become available in the future, these updates will be made available through Github.

Translators can use the Github system to see which changes are made and update their translations accordingly.

### CREDITS

Your efforts are much welcomed and to show our appreciation, your name and language are credited on the Credits page under Tools in the GUI.
Please let us know which credentials to use.

Thank you very much!
