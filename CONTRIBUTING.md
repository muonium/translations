### Before translating

The templates are en.json and fr.json

Example: I'm french, I know the French language very well, and I
want to translate to Spanish.

So, I copy fr.json to es.json, and I start to translate.

### ISO
The ISO used for naming is ISO 639.

For example:

French: fr

English: en

American: en-US

Estonian: et (not ee)

Arabic: ar

### Framework

```json
"global": {
  "home": "Encrypt your files",
  "about": "About",
  "adventure": "Achievement",
  "security": "Security",
  "blog": "Blog",
  "donate": "Donate",
  "help": "Help",
  "login": "Login",
  "register": "Register",
  "close": "Close"
},

```
Here, we see that "global" is the "category", it is used in the code to identify which "category" we'll use. (DO NOT OVERWIRTE)

"home" is the "id" of the translation text, it is used in the code to identify which text we'll display. (DO NOT OVERWIRTE)

"Encrypt your files" is the translation text, it's what you need to translate. (You can overwrite)

### Code Style

Please use following style: Indent mode `Spaces` and Indent size `2` in the Github web editor. If you have done this (you can adjust that at the top of the file next to `Edit file`) you can use tabs, they automatically will turn into two spaces.

### Mistakes

It doesn't matter if you made a/several mistakes, other contributors will correct your mistakes.

### Corrections

If you see a translation mistake, then you can open an issue or make a pull request.

### Pull Request

You can write your name or pseudo on AUTHORS in your PR.

/!\ **before merging, you need your PR to be reviewed and approved by at least three people speaking your language.**

Then, we suggest you to ask your friends or any other people you know that could review your PR on GitHub.
