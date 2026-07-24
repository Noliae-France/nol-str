# nol.str

Utilitaires de chaînes en pur [Nolc](https://noliae-nolc.s3.gra.io.cloud.ovh.net/nolc-latest-linux-x86_64.tar.gz), sans dépendance.

## Installation

```toml
[dependances]
"nol-str" = { git = "https://github.com/Noliae-France/nol-str" }
```

## API
`capitalise`, `titre`, `pad_gauche`, `pad_droite`, `tronque(max, suffixe)`, `compte(motif)`, `enleve_prefixe`, `enleve_suffixe`, `inverse`.

```nol
capitalise("bonjour")            // "Bonjour"
titre("le petit chat")           // "Le Petit Chat"
pad_gauche("7", 3, "0")          // "007"
tronque("bonjour", 4, "...")     // "b..."
```

## Licence

MIT © 2026 Bastien LANGUEDOC.
