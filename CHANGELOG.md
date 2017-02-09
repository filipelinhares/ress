## [v1.2.2]
- Also set `background-repeat: no-repeat` to pseudo elements (#14)

## [v1.1.2]
- Add missing comma on button elements selector

## [v1.1.1]
:tada: New feature and updates from Normalize

### Added:
- **[N]** Correct the display of `<summary>` in all browsers
- Apply cursor pointer to button elements - (#7)

### Removed:
- **[N]** Placeholder normalization

### Changed:
- Text selection color to improves a11y - Thanks @dcorb

**[N]**_ormalize updates._

## [v1.0.1]
Just README updates and code comments


## [v1.0.0]
#### :zap: sanilize.css renamed to ress

Before [Sanitize version 3.0.0](https://github.com/10up/sanitize.css/commit/8eb14223c1d5c928a2a51b17d4227849e7b5bdb7) be released, I was thinking about removing the description _"Merge between"_ from sanilize. Sanilize came with some deprecations that I wanted to keep and some new features that I wanted to remove.

Now with the release of [Sanitize version 4.0.0](https://github.com/10up/sanitize.css/commit/bf3d695016cbd5d17c89361d4273f3d5f69aa0ee) It's time to a new way.

Since the fork of sanitize, my goal with this project is to make a modern reset with crossbrowsers normalization. Now, **ress** has your own features and resets which you can use and customize.

The new cool features are documented in the [README](README.md/#features). The source code is clean and pretty documented, you can read it to learn something :smile:

## [v0.7.4]
- Release a landing page :smile: - [sanilize.css](http://filipelinhares.github.io/sanilize.css/)

### Removed:
- Remove unnecessary comments to keep the code clean
- Remove `list-style: none;` from `nav ul, nav ol`
- Remove `-ms-overflow-style: -ms-autohiding-scrollbar` from `html`

## [v0.7.3]
Updates from normalize 4.1.1


### Added:
- Normalize placeholder styles in Edge, Chrome, and Safari with Firefox
- Normalize file select buttons
- Remove gaps in links underline in iOS 8+ and Safari 8+

### Removed:
- Remove unnecessary specificity in inputs

### Changed:
- Correct the outline of search inputs in Chrome and Safari
- Limit Firefox focus normalization to buttons

## [v0.6.3]
Updates from normalize.css 4.0.0

### Added:
- Correct inconsistent `overflow` for `hr` in Edge and IE.
- Correct `legend` text wrapping not present in Edge and IE.

### Removed:
- Opinionated `table` resets.
- Opinionated `pre` overflow.

### Changed:
- Opinionated style of `outline-width` for `a:active` and `a:hover`.
- Update normalization of `border-style` for `img`.
- Update normalization of color inheritance for `legend`.
