_N.B. This is a fork of the_ [Source Code Pro repository](https://github.com/adobe/source-code-pro)

## Hasklig - Ligatures for Haskell code

Programming languages are limited to relatively few characters. As a result of a limited character set, combined character operators surfaced quite early, such as the widely used arrow (`->`), comprised of a hyphen and greater sign. It looks like an arrow if you know the analogy and squint a bit.

Composite glyphs are problematic in languages such as Haskell which utilize these complicated operators (`<-`, `::`, `=>`, `-<`, `>>=` etc.) extensively (_over 100 in_ `lens` _alone_!). The readability of this kind of complex code improves considerably with some kind of pretty printing.

Some Haskell programmers have resorted to unicode symbols in code as a solution (`⇒`, `←` _etc._). However, these symbols are one-character-wide and therefore eye-strainingly small.

Hasklig solves this problem the way typographers have always solved ill-fitting characters which co-occur often: ligatures. The underlying code stays the same — only the representation changes.

[**Download Hasklig Font Family v0.4**](https://github.com/i-tu/Hasklig/releases/download/0.4/Hasklig-0.4.zip)

#### Hasklig
![Hasklig Sample](hasklig_example.png?raw=true)

#### Source Code Pro
![Source Code Pro Sample](SourceCodeProSample.png?raw=true)

### Editors and Terminals with support
+ Atom (_add_ `text-rendering: optimizeLegibility;` _to your_ `.editor` _css._)
+ Chocolat
+ Geany
+ gEdit
+ Kate
+ Konsole
+ KWrite
+ Leksah (_x64 W8 reported not working_)
+ Smultron
+ TextEdit
+ TextMate (from version 2.0-alpha.9549)

### No support
- Aquamacs
- gVim (_output corrupted_)
- iTerm2
- MacVim
- Sublime Text (_Vote for the enhancement_ [**here**](http://sublimetext.userecho.com/topic/433445-/))
- Terminal (OSX)

## Release notes
+ v0.4: New ligatures: `<*`, `<*>`, `<+>`, `<$>`, `***`,  `<|>`, `!!`, `||`, `===`, `==>`. Powerline symbols (_in case you need them_)
+ v0.3: New ligatures: `<<<`, `>>>`, `<>` and `+++`
+ v0.2: Lengthened `==` and `/=` to match other equals signs
+ v0.1: Ligatures `<-`, `->`, `=>` `>>`, `<<`, `>>=`, `=<<`, `..`, `...`, `::`, `-<`, `>-`, `-<<`, `>>-`, `++`, `/=` and `==`
    
## Alternatives

- Vim: vim2hs and HaskellConceal do this but a ligature takes up one less space, changing vertical alignment
- Emacs: haskell-mode does the same as vim2hs, but emacs reportedly supports adjusting the font for ligatures so that proper spacing is maintained [**Instructions**](http://www.reddit.com/r/haskell/comments/23g9dv/oc_haskell_programming_font_with_ligatures/ch1srdy) _(note: I haven't been able to get this to work myself on OSX)_
