# Fushili Language

Welcome to the **[Fushili Language](https://project-mansion.fandom.com/zh-hk/wiki/%E8%BC%94%E8%A5%BF%E9%87%8C%E8%AA%9E)**  repository! <br>
Fushili is a custom-built language for Daton City using the hangul script, in which Daton is a city-state we are recreating in Minecraft Bedrock (Realms, ported to Java as world file) under the project title "Project Mansion" as a way to connect with distant friends and family who emigrated under the Hong Kong National Security Law of 2020. The purpose of this repository is to host the translator of the language, which is an embed HTML file. Tutorials for the language itself will be released soon, possibly in the Wiki Section of this repository.

# Fushili Translator Specific Instructions

## Information
**Supports but not optimised** for mobile.<br>
Enter **English on the left** and **Fushili appears on the right**. Reverse translation is **not supported**.

## If you encounter the translator not translating some words 🤔
### Punctuation
- Make sure you are putting a space after punctuation.<br>
- The first and last words in brackets or quotation marks will not be translated due to a bug in the engine running the translator. For example:
`"this is good"`<br>
- In this case, "this" and "good" would not be translated. A workaround is to add spaces:<br>
`" this is good "`

### Word forms
- Plural forms or adverbs, like "s" "es" "ies" "ly" are not fully translated due to the vast amount of workload. A work around can be adding suffixes like `-s`, `-es`, `-ies` and `-ly`, then manually editing the output.<br>
`(eg. lines ➔ line -s)`, `(oranges ➔ orange -s)`, `(vastly ➔ vast -ly)`.

### Translated words in brackets
- There are many words in English where there are two meanings in a single word.<br>
- Those words are usually separate words in Fushili, causing this to happen.<br>
- A future workaround that may be added is to add word state forms<br>
For example, if `"go"` in `"go to"` is indicated as a verb here, input `go(v)` to get the correct translation, `코레에`, and for other uses type `go(o)` to get `고`.

> State forms: <br>
> `(n)`: indicates the noun meaning of a word.<br>
> `(v)`: indicates the verb meaning of a word.<br>
> `(adj)`: indicates the adjective meaning of a word.<br>
> `(o)`: indicates the other meaning of a word.<br>
> `(ppl)`: allow translator to understand "Japanese" into "Japanese People"<br>
> `(lang)`: allow translator to understand "Japanese" into "Japanese Language"<br>
> `(’s)`: allow translator to understand "Japanese Food" into "Japan's Food"<br>
> `(q)`: indicates a question<br>
> `(num)`: indicates the word is a number.<br>
> `(art)`: indicates the word is an article.<br>
> `(drctn)`: indicates the word indicates a direction.<br>

- Example:<br>
- `where do we wait?` ➔ `(where[유헤레/뮤에 퍼라체]) 도 낫초멘 유아잍?`<br>
- `where(q) do we wait?` ➔ `뮤에 퍼라체 도 낫초멘 유아잍?`<br>

## Other Usage
If you want to make any changes, or use my code for your own translator website, feel free to use my HTML code(I'd love to see what you're using this for). Glad that it helped your project if you used it!

## License 
You can freely use or modify this project for personal or commercial purpose.(I'd love to see what you're using this for) 


Glad that it helped your project if you used it!
