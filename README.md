# vim-snippets

This is a meta repository for the snippets used by [my dotfiles](https://github.com/LunarWatcher/dotfiles), now separated out for trivial reusability by anyone interested.

Note that it's strongly recommended to combine this repo with [honza/vim-snippets](https://github.com/honza/vim-snippets), as this repo only defines additional snippets, with a couple overrides where they make sense.

Unlike honza's repo, however, this repo only supports UltiSnips, or other plugins able to parse UltiSnips snippets. There's no plan to add support for anything else, as this is the format I use. It's by no means the best format, but it has effectively won the format war for the time being; no better alternatives exist that also support code, required for some of the snippets in this repo (such as the timestamp snippets), and is actively maintained.

These snippets do contain some weird and niche snippets primarily aimed at my setup and conventions. For example, the shell snippets include snippets for development and production setup of PSQL databases, and markdown contains some stuff for a standard CONTRIBUTING.md I use.
