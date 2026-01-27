+++
title = "About ZolaNight"
template = "page.html"
+++

ZolaNight is a dark theme for the Zola static site generator. It is inspired by the Tokyo Night color scheme.

## Features

*   Dark theme
*   4 color schemes: `tokyonight`, `tokyostorm`, `tokyomoon`, `tokyoday`
*   Responsive design
*   Syntax highlighting for code blocks
*   Easy to customize

## How to use

To use this theme, you need to have Zola installed.

1.  Download the theme and place it in your `themes` directory.
2.  Update your `zola.toml` file to use the theme:

    ```toml
    theme = "zolanight"
    ```

3.  To use the sample content, copy the `content` directory from the theme to your project's root directory.
4.  To change the color scheme, update your `zola.toml` file:

    ```toml
    [extra.zolanight]
    theme = "tokyostorm"
    ```
