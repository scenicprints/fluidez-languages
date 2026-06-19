# Fluidez — Language Registry

This repo holds languages.json, the list of languages the Fluidez app offers.

To ADD a language:
  1. Create a new content repo (e.g. fluidez-pt-br) with a /content folder.
  2. Add an entry to languages.json with that repo's user/repo/branch.
That's it — the app will show the new language automatically.

Entry format:
  {
    "code":   "es-ni",              unique short code
    "name":   "Nicaraguan Spanish", shown in the picker
    "flag":   "🇳🇮",                emoji flag (optional)
    "user":   "scenicprints",       GitHub username
    "repo":   "fluidez-es-ni",      content repo name
    "branch": "main"                usually main
  }
