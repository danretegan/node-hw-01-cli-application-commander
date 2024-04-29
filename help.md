# Foloseste urmatoarele comenzi

### Obținerea și afișarea întregii liste de contacte sub formă de tabel (console.table):

`node index.js -a list`

### Obținerea unui contact după id:

`node index.js -a get -i idxyz123 `
_inlocuieste 'idxyz123' cu id-ul dorit!_

### Adăugarea unui contact:

`node index.js -a add -n "Numele Persoanei" -e "email@exemplu.com" -p "123-456-7890"`
_foloseste ghilimele daca sirul de introdus este format din doua sau mai multe elemente: "Numele Persoanei"._

### Ștergerea unui contact:

`node index.js -a remove -i idxyz123`
_inlocuieste 'idxyz123' cu id-ul dorit!_

### Help:

`node index.js -h`
