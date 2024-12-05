# appa-N.C
//https://github.com/ncikovic/appa-N.C..git
*SELECT knjiga.naslov
FROM knjiga
JOIN autor ON knjiga.autor = autor.id
WHERE autor.prezime_ime = 'Andrić Ivo'
ORDER BY knjiga.naslov ASC*
