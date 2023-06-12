[![English](https://img.shields.io/badge/Language-English-blue.svg)](https://github.com/ryaeung/fushili/blob/main/README.md)
[![日本語](https://img.shields.io/badge/言語-日本語-yellow.svg)](https://github.com/ryaeung/fushili/blob/main/README.jp.md)
[![푸서히리](https://img.shields.io/badge/구넷노-푸서히리-brightgreen.svg)](https://github.com/ryaeung/fushili/blob/main/README.fs.md)

---

# 輔西里語

▪️ 歡迎來到 [輔西里語](https://project-mansion.fandom.com/zh-hk/wiki/%E8%BC%94%E8%A5%BF%E9%87%8C%E8%AA%9E) 的 Github 倉儲！<br><br>

▪️ 輔西里語是一種使用**韓語諺文文字的自創語言，用於名為達通城的一個虛構城市**。<br><br>

▪️ 達通城是名為 **"Project Mansion"** 旗下建造的一個獨立城市，在**Minecraft基岩版([Realms在線伺服器](https://realms.gg/J5gUEa62Yss)，匯出為Java世界檔案)。** 希望與因2020年香港國家安全法而移民他鄉的親友藉此平台保持聯繫。 <br><br>

▪️ 這個倉儲的目的是**寄存該語言的翻譯器**，它是一個嵌入HTML文件。語言本身的教程稍遲會發布，發布位置可能於倉儲的Wiki部分。

## 🌸資訊
- 支援，但**尚未針對行動電話等裝置**優化。<br>
- 在網頁左側視窗輸入**英文**，右側便會顯示**輔西里語**。不支援反向翻譯。

## 🌸如果翻譯器出現「漏翻」情況
### 🔍標點符號
- 確保標點符號為正規英文半形標點。<br>
> 正確：Hi, I am happy.<br>
> 錯誤：Hi，I am happy。<br>

- 確保標點符號後面有放一個空格。<br>
> 正確：Hi, I am happy.<br>
> 錯誤：Hi,I am happy.<br>

- 括號或引號中的第一個和最後一個英文單詞將不會被翻譯。理由為翻譯器引擎自身無法修復的BUG。
> `"this is good"`<br>
> 在這種情況下，“this”和“good”將不會被翻譯。解決方法是添加空格: `" this is good "`

### 🔍單詞形式
- 含有複數形式或副詞的字，如`“s”` `“es”` `“ies”` `“ly”` 等，加入的話涉及的工作量巨大，所以無法支持翻譯。解決方法可以是**在字後添加 suffix**，如 `-s`，`-es`，`-ies`和`-ly`，然後再用其他文字編輯器微調。<br>
> lines ➔ line -s <br> 
> oranges ➔ orange -s <br>
> vastly ➔ vast -ly <br><br>

- **以下是添加後綴之前和之後的比較：**<br>
  - 像下圖“products”這樣的單詞至少可以部分翻譯（然後只需批量尋找取代` -`）
  
![添加單詞形式之前和之後的比較](https://cdn.discordapp.com/attachments/1102284286880645165/1110140409163808858/2023-05-22_5.41.33.png)

## 🌸一字多義
- 有許多英文單字在一個單詞中有兩個意思（例如 right 可以理解為「右邊」或「權利」。）
- 這些單詞通常在輔西里語是不同的單詞，從而導致這種情況發生。
- 未來可能添加的解決方法是添加「單詞狀態形式」區分英文字詞的意思，缺點是用者需要知道英文單詞的意思（目前不支援）。<br>
- 未來也有機會可以識別某些一字多義的情況。例如："right" 可能在 "the right" 的語境下識別為權利並翻譯成 `릭헡`，其他語境則維持預設 `[right(릭헡/미기)]`。

如果這項功能真的加入了，可以這樣用：<br><br>

如果你想輸入 “go to” ，此處的 “go to” 中的 “go” 被表示為動詞，輸入“go(v)”便可以獲取正確的翻譯“코레에”，
對於其他用法，你可以輸入“go(o)”以獲取“고”。

> 「單詞狀態形式」...（不知道會不會加）：<br>
> `(n)` ：指詞的名詞含義。<br>
> `(v)` ：指詞的動詞含義。<br>
> `(adj)` ：指詞的形容詞含義。<br>
> `(o)` ：指詞的其他含義。<br>
> `(ppl)` ：允許翻譯器將英語的“Japanese”理解為“日本人”。<br>
> `(lang)` ：允許翻譯器將英語的“Japanese”理解為“日語”。<br>
> `('s)` ：允許翻譯器將英語的“Japanese”理解為“日本的〇〇”。<br>
> `(q)` ：指出問題。<br>
> `(num)` ：表示該詞是一個數字。<br>
> `(art)` ：表示詞是一個冠詞 (a, an, the)。<br>
> `(drctn)` ：表示詞指示方向。<br><br>

- 示例：
> `where do we wait?` ➔ `(where[유헤레/뮤에 퍼라체]) 도 낫초멘 유아잍?`<br>
> `where(q) do we wait?` ➔ `뮤에 퍼라체 도 낫초멘 유아잍?`

![Future usage of word states](https://cdn.discordapp.com/attachments/1102284286880645165/1110159045433774100/2023-05-22_6.55.36.png)

## 🌸其他使用和許可
- 如果您想進行任何修改，或將我的代碼用於自己的網站，歡迎隨時使用！<br>
- （很想看看你用這個來做什麼）。<br>
- 如果您使用它我很榮幸！
