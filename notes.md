

contents stored in papers.bib
config file at `~/.config/papers.json`


get bibcite to clipboard
` papers extract PAPER.pdf | xclip`

rename papers
`papers filecheck -r`


adding new paper workflows (consider optimizing):

`find ~/Downloads/ -mmin -1 | xargs mv -t ~/docs/papers/`
`papers add NEW_PAPER.pdf`
`papers filecheck -r`



