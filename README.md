[![正體中文](https://img.shields.io/badge/語言-正體中文-red.svg)](https://github.com/ryaeung/fushili/blob/main/README.zh-Hans.md)

# Fushili Language

▪️ Welcome to the **[Fushili Language](https://project-mansion.fandom.com/zh-hk/wiki/%E8%BC%94%E8%A5%BF%E9%87%8C%E8%AA%9E)**  repository! <br><br>

▪️ Fushili is a **custom-built language for Daton City using the hangul script**.<br><br>

▪️ Daton is a **city-state we are recreating in Minecraft Bedrock ([Realms](https://realms.gg/J5gUEa62Yss), ported to Java as world file) under the project title "Project Mansion"** as a way to **connect with distant friends and family** who emigrated under the Hong Kong National Security Law of 2020. <br><br>

▪️ The purpose of this repository is to **host the translator of the language**, which is an embed HTML file. Tutorials for the language itself will be released soon, possibly in the Wiki Section of this repository.

## 🌸Information
- **Supports but not optimised** for mobile.<br>
- Enter **English on the left** and **Fushili appears on the right**. Reverse translation is **not supported**.

## 🌸If you encounter the translator not translating some words
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
- A future workaround that may be added is to add **word state forms** (currently <em> NOT </em> supported yet)<br>
For example, if `"go"` in `"go to"` is indicated as a verb here, input `go(v)` to get the correct translation, `코레에`, and for other uses type `go(o)` to get `고`.

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
