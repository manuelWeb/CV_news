# README


## Persona CONFORT ET VIE

*catalogue senior pour rendre plus facile la vie de tous les jours*

- 123rf.com
- [ Suivre ce lien ]( https://es.123rf.com/photo_21341289_mujer-mayor-de-risa-que-miente-en-un-sof%C3%A1-frente-a-la-c%C3%A1mara-con-una-sonrisa-radiante-mirando-hacia-copy.html )

## items CV

- CONFORT & BIEN-ETRE
- IDÉES VIE FACILE
- NUIT / RELAX
- VÊTEMENTS & ACCESSOIRES

```css
.nav {
  font-family: Verdana, Geneva, sans-serif;
}
```

## Short news nav

```javascript
// get primary nav item text !important CLASS IS ON NEWS.NAV
const txtAry = Array.from(document.querySelectorAll('.univ'))
txtAry.map( (i) => console.log( i.innerHTML.replace(/&amp;/g,'&') ) )
```

## Grid 

- Total width : 636px -> marges ext (hors grille 6px X2)
- Grid total width 624px (external marges 4px 2X)
- Vertical rythm 8px Gutter height 8px | Row Height 4 x Gutter Height

| column | column width | gutter width | external gutter |
| :---:  | :---:        | :---:        | :---:           |
| 12     | 44           | 8            | 4               |


## alias service internet archive

rm -rf remote_alias && ln -s '/Volumes/service internetArchives$/NEWSLETTERS/TRIGGER/RELANCE_PANIER/CONFORT_VIE' remote_alias && open remote_alias
