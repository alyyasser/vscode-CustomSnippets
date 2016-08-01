# Custom Snippets

[Custom Snippets][marketplace-url] is code snippet for creating your own snippets.

## Demo

#### Custom Snippets: Single Line

![Custom Snippets: Single-line][demo-single-img]

#### Custom Snippets: Multiple Lines

![Custom Snippets: Multi-line][demo-multiple-img]

#### Custom Snippets: Multiple Lines on Body

![Custom Snippets: Multiple-line body][demo-body-img]

## Installation

1. Visit [VSCode Market: Custom Snippets][marketplace-url].<br><br>**OR**

2. By VSCode
   * Open VSCode
   * Launch VS Code Quick Open (press **Ctrl+P**) 
   * Paste the following command

     ```
     ext install vscode-custom-snippets
     ```
   * Press **Enter** to search the extension
   * Select **Custom Snippets** 
   * Install

> **Tip:** If you open [README][readme-url] on GitHub, you can install [Clipboardy][clipboardy-chrome-webstore], a Chrome extension, for copying the command listed above to clipboard.
> For more information, please visit [Clipboardy Chrome Extension Homepage][clipboardy-homepage].

## Usage

Type snippet prefix, and IntelliSense will show the snippet. If IntelliSense doesn't show the snippet, press **Ctrl+Space** and then **Enter** to insert the snippet.

Snippet Name | Prefix | Description
--- | --- | ---
[snippetSingleLine][demo-single-src-url] | `snippet-single` | [Create a custom snippet with a single body][demo-single-url]
[snippetMultiLine][demo-multiple-src-url] | `snippet-multi` | [Create a custom snippet with multiple lines][demo-multiple-url]
[snippetMultiLineBody][demo-body-src-url] | `snippet-multi-body` | [Add another snippet on the body of multi-line custom snippet][demo-body-url]

[marketplace-url]: https://marketplace.visualstudio.com/items?itemName=NgekNgok.vscode-custom-snippets
[readme-url]: https://github.com/alyyasser/vscode-CustomSnippets/blob/master/README.md

[demo-single-url]: #custom-snippets-single-line
[demo-single-src-url]: snippets/snippets.json#L2
[demo-single-img]: images/demo-single.gif "Create Custom or User snippet with single line body"

[demo-multiple-url]: #custom-snippets-multiple-lines
[demo-multiple-src-url]: snippets/snippets.json#L13
[demo-multiple-img]: images/demo-multiple.gif "Create Custom or User snippet with multiple line body"

[demo-body-url]: #custom-snippets-multiple-lines-on-body
[demo-body-src-url]: snippets/snippets.json#L26
[demo-body-img]: images/demo-body.gif "Add snippet body to multi-line Custom or User snippet"

[clipboardy-chrome-webstore]: https://chrome.google.com/webstore/detail/clipboardy/gkafpbdjggkmmngaamlghmigadfaalhc
[clipboardy-homepage]: https://rainsoft.io/clipboardy-chrome-extension
