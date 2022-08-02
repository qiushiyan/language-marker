# language-marker

A quarto extension to display the language for code blocks.

Currently only includes some of my commonly used languages:

- Python
- R
- SQL
- JavaScript
- TypeScript
- bash
- C++
- Rust
- Java

## Installation

To install this extension in your current directory (or into the Quarto project that you're currently working in),  use the following command:

```
quarto install extension qiushiyan/language-marker
```

## Enabling

Add this to your document or project options:

```yaml
filters:
  - language-marker
```

## Usage

```{.python display-language}
import matplotlib.pyplot as plt
plt.plot([1,23,2,4])
plt.show()
```
