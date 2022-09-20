# JSON-Resume-Paper

This is a theme for [JSON Resume](http://jsonresume.org/) based on https://github.com/TimDaub/jsonresume-theme-paper.

It inherited `media="print"` stylesheet for browser's **Print to PDF** to convert resume from `.html` to `.pdf`, with some additional tweaks of the layout
- Relocate section `Profile` to be after `Contact` 
- Support `.summary[]` and `.highlights[]` in section `Education`

Put your `resume.json` in this folder, and run `resume serve --theme .`.
You should now see this message:
```
Preview: http://localhost:4000
Press ctrl-c to stop
```

Customize `resume.template` for theme.

More on the requirement, installation, and demo on https://github.com/TimDaub/jsonresume-theme-paper.
