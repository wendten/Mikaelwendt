# Mikaelwendt

Gratis GitHub Pages hosting til Mikael Wendts portfolio.

## Filplacering

Læg hjemmesidefilerne direkte i roden af dette repository:

```text
index.html
style.css
script.js
assets/
images/
```

`index.html` skal ligge i roden. Det er den fil, GitHub Pages åbner først.

## GitHub Pages opsætning

Gå til:

```text
Settings > Pages
```

Vælg:

```text
Source: Deploy from a branch
Branch: main
Folder: /root
```

Siden vil normalt ligge på:

```text
https://wendten.github.io/Mikaelwendt/
```

## Vigtigt

Brug relative paths i HTML, CSS og JavaScript:

```html
<img src="assets/mikael-full-body.png" alt="Mikael Wendt">
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
```

Undgå paths der starter med `/`, fordi repoet bliver hostet under `/Mikaelwendt/`.
