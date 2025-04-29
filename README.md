# CLI_One_Liners
A Page with useful command line one liners. 


## ripgrep

### Find Python Scripts Containing A Given String
```bash
rg --color=always --glob '*.py' 'YOUR TEXT HERE'
```

rg: Calls ripgrep.
*	--color=always: Always show matches in color (for terminal readability).
*	--glob '*.py': Only search inside files ending with .py.
*	'YOUR TEXT HERE': The literal string you are searching for.
*	(Default behaviour is recursive, so no -r needed.)
