# Elvaradas: svetainės atnaujinimo eskizas

UAB „Elvaradas“ (elvaradas.lt) svetainės atnaujinimo prototipas. Vienas statinis puslapis: HTML, CSS ir vanilla JS, be build žingsnio.

## Kas viduje

- `index.html`: visas puslapis (struktūra, stiliai, logika).
- `img/`: nuotraukos. Pavyzdinės nuotraukos iš Unsplash (nemokama licencija), atestatų skenai paimti iš dabartinės elvaradas.lt.

## Peržiūra vietoje

```bash
npx http-server . -p 8080 -c-1
```

Tada atidarykite http://localhost:8080.

## Turinio valdymas

Prie adreso pridėjus `#admin`, atsidaro turinio redaktorius. Pakeitimai išsaugomi tik tada, kai puslapis atidarytas kaip Claude artifact (duomenų bazė `db`). Atidarius failą tiesiogiai, redaktorius veikia peržiūros režimu ir nieko neišsaugo.

## Žinomos spragos

- Nuotraukos pavyzdinės, reikia tikrų objektų nuotraukų.
- Atestatų skenuose galiojimas iki 2014 m., reikia naujų.
- Logotipas perpieštas Anton šriftu, geriau naudoti originalų vektorinį failą.
