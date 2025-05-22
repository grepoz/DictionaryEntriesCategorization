For provided file with dictionary with 50k entries from https://github.com/hermitdave/FrequencyWords, which has a format like
```txt
hazardzista 243 
wróciłbym 243
półkach 243
niezdolna 243
zwolennik 775 osoba
```
program generates txt file with all nouns and category assigned to them
```txt
hazardzista 243 osoba
zwolennik 775 osoba
```

Supports multiple languages that are supported by Google Translate API

Limitations:
- for robust and fast processing provided file should have reasonable size