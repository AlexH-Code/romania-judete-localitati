# romania-judete-localitati – Date și Structură

Acest repository conține fișiere cu localitățile din România, utile pentru aplicații de integrare, validare și procesare a adreselor.

## Structura fișierelor

- **localitati.json** – Listă simplă cu localități, format JSON (județ auto, județ complet, localitate), cu si fara diacritice.
- **orase.json** – Listă de orașe în format JSON (structura detaliată în fișier).


## Format fișiere

### localitati.json
```json
[
  {
    "JUDET_AUTO": "B",
    "JUDET": "București",
    "NUME": "Municipiul București",
    "NUME_STANDARD": "Municipiul Bucuresti"
  }, //etc.
]
```

### orase.json
```json
  [
    "B, București, Municipiul București",
    "B, București, Sectorul 1",
    "B, București, Sectorul 2",
    "B, București, Sectorul 3",
    //etc.
  ]
```

## Surse date:

Datele au fost colectate din surse publice.

## Contribuții

Orice corectare sau completare este binevenită! Trimiteți un pull request sau deschideți un issue pentru propuneri.

## Licență

Acest set de date este distribuit sub licența [MIT](LICENSE). Poate fi folosit, modificat și redistribuit liber, cu respectarea termenilor licenței MIT.
