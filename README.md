# Mystic Payment Calculator

Kalkulačka pro výpočet plateb za registraci na Mystic Skate Cup.

## Použití na webových stránkách

Kalkulačku lze vložit na libovolnou webovou stránku pomocí iframe:

```html
<iframe src="calc.html?lang=cz" width="600" height="800" frameborder="0"></iframe>
```

### Parametry URL

- `lang` - jazyk kalkulačky
  - `cz` - česká verze
  - `en` - anglická verze

Příklad použití s českou verzí:
```html
<iframe src="calc.html?lang=cz" width="600" height="800" frameborder="0"></iframe>
```

Příklad použití s anglickou verzí:
```html
<iframe src="calc.html?lang=en" width="600" height="800" frameborder="0"></iframe>
```

## Konfigurace

Konfigurační soubor `config.json` obsahuje:
- Bankovní údaje pro platby v CZK a EUR
- Ceny za soutěže a doprovod
- Informace o příjemci platby
