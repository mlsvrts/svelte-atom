# Svelte for Atom

Fork of ide-svelte that includes an up-to-date language server:

Provides syntax highlighting and rich intellisense for Svelte components in Atom, utilising the [svelte language server](https://github.com/UnwrittenFun/svelte-language-server).

## Why does this exist?

The parent of this plugin, [svelte-atom](https://github.com/sveltejs/svelte-atom) hasn't seen an update in two years and is
missing critical features like Svelte 3 support. Thus, ide-svelte-2.
If there's interest, CI for keeping the language server version up to date automatically may be added. Until then:

The current svelte language server version is 0.11.0

## Features

-   Svelte
    -   Diagnostic messages for warnings and errors
    -   Support for svelte preprocessors that provide source maps
-   HTML
    -   Hover info
    -   Autocompletions
    -   [Emmet](https://emmet.io/)
    -   Formatting
    -   Symbols in Outline panel
-   CSS / SCSS / LESS
    -   Diagnostic messages for syntax and lint errors
    -   Hover info
    -   Autocompletions
    -   Formatting (via [prettier](https://github.com/prettier/prettier))
    -   [Emmet](https://emmet.io/)
    -   Color highlighting and color picker
    -   Symbols in Outline panel
-   TypeScript / JavaScript
    -   Diagnostics messages for syntax and semantic errors
    -   Hover info
    -   Formatting (via [prettier](https://github.com/prettier/prettier))
    -   Symbols in Outline panel

More features coming soon.

## See Also

-   [Svelte Language Server](https://github.com/UnwrittenFun/svelte-language-server)
-   [Svelte VS Code](https://github.com/UnwrittenFun/svelte-vscode)
