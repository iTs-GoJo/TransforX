# py-translator

Simple Python translation library using Google Translate unofficial API.

## Installation

```bash
pip install py-translator
```

- - -

## Usage
```python
from py_translator import translate

print(translate("سلام دنیا", to_lang="en"))
# Output: Hello World

print(translate(["سلام", "دنیا"], to_lang="en"))
# Output: ['Hello', 'World']
```

- - -

## Features
• Translate a text or a list of texts.\n
• Auto-detect source languages.
• No Api-Key Requested.

- - -
# LICENSE
The project is published with MIT License.