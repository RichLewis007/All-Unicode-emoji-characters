# Markdown Table Border Examples

This file shows a few common ways to "box" content in GitHub-flavored Markdown.
All content below is dummy text.

## 1) ASCII Box (code block)

```
+----------------------------------------------+
| Dummy title                                  |
+----------------------------------------------+
| Lorem ipsum dolor sit amet, consectetur      |
| adipiscing elit, sed do eiusmod tempor.      |
+----------------------------------------------+
```

## 2) Two-column Markdown table

| Dummy column A | Dummy column B |
| -------------- | -------------- |
| Alpha text     | Beta text      |
| Gamma text     | Delta text     |

## 3) One-column Markdown table

| Dummy boxed text                                         |
| -------------------------------------------------------- |
| Lorem ipsum dolor sit amet, consectetur adipiscing elit. |

## 4) Three-column Markdown table (aligned)

| Left | Center | Right |
| :--- | :----: | ----: |
| A1   |   B1   |    C1 |
| A2   |   B2   |    C2 |

## 5) Table with longer wrapped text

| Dummy heading | Dummy detail                                                                                                                |
| ------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Item one      | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. |
| Item two      | Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.                 |

## 6) HTML centering supported by GitHub

<p align="center">Centered dummy text using a paragraph tag.</p>

<div align="center">Centered dummy text using a div tag.</div>

## 7) ASCII box inside a pre tag

<pre>
+----------------------------------------------+
| Dummy title                                  |
+----------------------------------------------+
| Lorem ipsum dolor sit amet, consectetur      |
| adipiscing elit, sed do eiusmod tempor.      |
+----------------------------------------------+
</pre>

## 8) Keyboard key tag examples

Use HTML <kbd> tags to style keys:

<kbd>Ctrl</kbd> + <kbd>C</kbd> • <kbd>Ctrl</kbd> + <kbd>V</kbd> • <kbd>Cmd</kbd> + <kbd>F</kbd> • <kbd>Option</kbd> + <kbd>F</kbd> • <kbd>Shift</kbd> + <kbd>Tab</kbd> • <kbd>Esc</kbd>

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<blockquote> (block quotes) asdfasdf/blockquote>

> # Foo
>
> bar
> baz

> # Foo
>
> bar
> baz

> # Foo
>
> bar
> baz

     > # Foo
    > bar
    > baz

<p>Text on the left <img align="right" src="link/to/the/picture"></p>

<p align="center">...</p>
<div align="center">...</div>
<p align="right">...</p>
<p align="justify">...</p> (often works)

## 9) Supported vs unsupported (GitHub rendering)

Supported:

```
<p align="center">...</p>
<div align="center">...</div>
<p align="right">...</p>
<p align="justify">...</p>
```

Unsupported:

```
<p style="text-align:center">...</p>
<span style="color:red">...</span>
<p class="my-class">...</p>
<p id="my-id">...</p>
<style>p { color: red; }</style>
<font color="red">...</font>
```

## 10) Modifier key SVGs (outline vs filled)

These SVGs are created in this repo and are free to use.

| Key    | Outline                                                | Filled                                               |
| ------ | ------------------------------------------------------ | ---------------------------------------------------- |
| Ctrl   | ![Ctrl outline](assets/key-icons/outline/ctrl.svg)     | ![Ctrl filled](assets/key-icons/filled/ctrl.svg)     |
| Cmd    | ![Cmd outline](assets/key-icons/outline/cmd.svg)       | ![Cmd filled](assets/key-icons/filled/cmd.svg)       |
| Option | ![Option outline](assets/key-icons/outline/option.svg) | ![Option filled](assets/key-icons/filled/option.svg) |
| Shift  | ![Shift outline](assets/key-icons/outline/shift.svg)   | ![Shift filled](assets/key-icons/filled/shift.svg)   |
| Alt    | ![Alt outline](assets/key-icons/outline/alt.svg)       | ![Alt filled](assets/key-icons/filled/alt.svg)       |

| Find emojis fast (use "Find in page" on this doc)                                                                                                                                                                                                                                                                                   |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="assets/browser-icons/simple-icons/googlechrome.svg" width="16" height="16" alt="Chrome"> <img src="assets/browser-icons/simple-icons/microsoftedge.svg" width="16" height="16" alt="Edge"> **Chrome / Edge (Windows, Linux)**: Press <kbd>Ctrl</kbd> + <kbd>F</kbd>, type a word like "smile", "heart", or the emoji name |
| <img src="assets/browser-icons/simple-icons/googlechrome.svg" width="16" height="16" alt="Chrome"> <img src="assets/browser-icons/simple-icons/microsoftedge.svg" width="16" height="16" alt="Edge"> **Chrome / Edge (macOS)**: Press <kbd>Cmd</kbd> + <kbd>F</kbd>                                                                 |
| <img src="assets/browser-icons/simple-icons/firefoxbrowser.svg" width="16" height="16" alt="Firefox"> **Firefox (Windows/Linux)**: Press <kbd>Ctrl</kbd> + <kbd>F</kbd>                                                                                                                                                             |
| <img src="assets/browser-icons/simple-icons/firefoxbrowser.svg" width="16" height="16" alt="Firefox"> **Firefox (macOS)**: Press <kbd>Cmd</kbd> + <kbd>F</kbd>                                                                                                                                                                      |
| <img src="assets/browser-icons/simple-icons/safari.svg" width="16" height="16" alt="Safari"> **Safari (macOS)**: Press <kbd>Cmd</kbd> + <kbd>F</kbd>                                                                                                                                                                                |
| <img src="assets/browser-icons/simple-icons/safari.svg" width="16" height="16" alt="Safari"> **Safari (iOS/iPadOS)**: Tap the Share button, then "Find on Page"                                                                                                                                                                     |
| <img src="assets/browser-icons/simple-icons/googlechrome.svg" width="16" height="16" alt="Chrome"> **Chrome (Android)**: Tap the menu (three dots) then "Find in page"                                                                                                                                                              |
