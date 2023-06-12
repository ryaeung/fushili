[![English](https://img.shields.io/badge/Language-English-blue.svg)](https://github.com/ryaeung/fushili/blob/main/README.md)
[![正體中文](https://img.shields.io/badge/語言-正體中文-red.svg)](https://github.com/ryaeung/fushili/blob/main/README.zh-Hans.md)
[![푸서히리](https://img.shields.io/badge/구넷노-푸서히리-brightgreen.svg)](https://github.com/ryaeung/fushili/blob/main/README.fs.md)

---
# フッシリー語（ダトン語）

▪️ **[フッシリー語](https://project-mansion.fandom.com/zh-hk/wiki/%E8%BC%94%E8%A5%BF%E9%87%8C%E8%AA%9E)** のギットハブリポジトリへようこそ！ <br><br>

▪️ フッシリー語は、**ハングルの文字でダトン城のため作った独自言語**です。<br><br>

▪️ ダトン城は、「プロジェクト・マンション」というタイトルの下、マインクラフトBedrock版（Realms）で再現している都市国家です（Java版の場合はマップある）。このプロジェクトは、2020年に制定された「香港国家安全法」の下で移住した遠く離れた友人や家族と繋がるために行われています。 <br><br>

▪️ このリポジトリの目的は、**言語のトランスレーターである埋め込みHTMLファイルをホストすること**です。言語自体のチュートリアルも近日中にWikiセクションで公開される予定です。

## 🌸情報
- スマホに**対応するけど、最適化はされていない**。<br>
- **左に英語を入力して**、右にフッシリー語を現れる。**逆翻訳ができない。**

## 🌸トランスレーターが翻訳していない単語ある場合
### 🔍Punctuation
- Make sure you are putting a space after punctuation.<br>
> Correct: Hi, I am happy.<br>
> Wrong: Hi,I am happy.
- The first and last words in brackets or quotation marks will not be translated due to a bug in the engine running the translator.
> `"this is good"`<br>
> In this case, "this" and "good" would not be translated. A workaround is to add spaces: `" this is good "`

### 🔍Word forms
- Plural forms or adverbs, like "s" "es" "ies" "ly" are not fully translated due to the vast amount of workload. A work around can be **adding suffixes** like `-s`, `-es`, `-ies` and `-ly`, then manually editing the output.<br>
> lines ➔ line -s <br> 
> oranges ➔ orange -s <br>
> vastly ➔ vast -ly <br><br>

- **Below is a comparison of before vs after adding word forms:**<br>
  -  Words like "products" gets to at least be partially translated (then just find and replace ` -` into null)
![Before vs After adding word forms](https://cdn.discordapp.com/attachments/1102284286880645165/1110140409163808858/2023-05-22_5.41.33.png)
                                                                                                                                  

### 🔍Translated words in brackets as output
- There are many words in English where there are two meanings in a single word.<br>
- Those words are usually separate words in Fushili, causing this to happen.<br>
- A future workaround that may be added is to add **word state forms**. A flaw of this feature is that the user must know and determine the context of the English words themselves (currently <em> NOT </em> supported yet)<br>
For example, if `"go"` in `"go to"` is indicated as a verb here, input `go(v)` to get the correct translation, `코레에`, and for other uses type `go(o)` to get `고`.
- There will be more support for ambiguity to the translator. For example, the word "right" may be automatically referenced by context as `릭헡` in "the right to..." but kept as `[right(릭헡/미기)]` in other cases.

**State forms... maybe:** <br>
  >   `(n)`: indicates the noun meaning of a word.<br>
  >   `(v)`: indicates the verb meaning of a word.<br>
  >   `(adj)`: indicates the adjective meaning of a word.<br>
  >   `(o)`: indicates the other meaning of a word.<br>
  >   `(ppl)`: allow translator to understand "Japanese" into "Japanese People"<br>
  >   `(lang)`: allow translator to understand "Japanese" into "Japanese Language"<br>
  >   `(’s)`: allow translator to understand "Japanese Food" into "Japan's Food"<br>
  >   `(q)`: indicates a question<br>
  >   `(num)`: indicates the word is a number.<br>
  >   `(art)`: indicates the word is an article.<br>
  >   `(drctn)`: indicates the word indicates a direction.<br>

- Example:<br>
> `where do we wait?` ➔ `(where[유헤레/뮤에 퍼라체]) 도 낫초멘 유아잍?`<br>
> `where(q) do we wait?` ➔ `뮤에 퍼라체 도 낫초멘 유아잍?`<br>

![Future usage of word states](https://cdn.discordapp.com/attachments/1102284286880645165/1110159045433774100/2023-05-22_6.55.36.png)

## 🌸Other Usage and License
- If you want to make any changes, or use my code for your own translator website, feel free to use my HTML code!<br>
- (I'd love to see what you're using this for). <br>
- Glad that it helped your project if you used it!
