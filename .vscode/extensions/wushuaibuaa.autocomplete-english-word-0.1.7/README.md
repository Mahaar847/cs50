# English word hint (auto-completion) for Visual Studio Code


## Installation

1. Press Ctrl+Shift+X to open the Extensions tab
2. Type **English word hint** to find the extension
3. Click the Install button, then the Enable button

## Hint Support

1. When editing a **markdown** file and **latex** file in Code with **English word hint** installed, any type of English words will trigger a hint of word and give the explanation.


## Usage

Becase the markdown does not support quick suggestions in default. Therefore, the hint will not appear when type in markdown file. Below configure should be set by user.

```json
"[markdown]": {
        "editor.quickSuggestions": true
    }
```

## Declaration

1. Open source license of this extension is [GPL-3.0](https://github.com/wushuaibuaa/vsautocomplete-en-en/blob/master/LICENSE)

## Contributing to the Extension

File description:

- `extension/main.js` extension main script files
- `hint_data/words.json` hint data json file from Oxford dictionary.

## Author

[Wushuai](https://github.com/wushuaibuaa)
