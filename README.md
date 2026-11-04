# Salasanan vahvuustarkistin · Kontroll av lösenordsstyrka · Password Strength Checker

Python-ohjelmointi 1 · tehtävä 3 · uppgift 3 · assignment 3

## Suomeksi: Salasanan vahvuustarkistin

### Tehtävä

Kirjoita ohjelma, joka lukee salasanan ja tarkistaa silmukan ja merkkijonometodien avulla, onko se vahva. Salasana on vahva, kun se täyttää kaikki neljä ehtoa: vähintään 8 merkkiä, vähintään yksi iso kirjain, vähintään yksi pieni kirjain ja vähintään yksi numero.

### Syöte

Yksi rivi: salasana.

### Tuloste

Täsmälleen `Strong password` tai `Weak password`.

### Esimerkit

Syöte 1:

```text
Salasana123
```

Tuloste 1:

```text
Strong password
```

Syöte 2:

```text
salasana123
```

Tuloste 2:

```text
Weak password
```

Syöte 3:

```text
Lyhyt1a
```

Tuloste 3:

```text
Weak password
```

### Työskentely

Kirjoita ratkaisu tiedostoon `main.py`. Testaa ohjelma esimerkkisyötteillä komennolla `python3 main.py`, commitoi kun jokin osa toimii ja pushaa viimeisin versio GitHubiin ennen palautusaikaa.

## På svenska: Kontroll av lösenordsstyrka

### Uppgift

Skriv ett program som läser ett lösenord och med en loop och strängmetoder kontrollerar om det är starkt. Lösenordet är starkt när det uppfyller alla fyra villkor: minst 8 tecken, minst en stor bokstav, minst en liten bokstav och minst en siffra.

### Indata

En rad: lösenordet.

### Utskrift

Exakt `Strong password` eller `Weak password`.

### Exempel

Indata 1:

```text
Salasana123
```

Utskrift 1:

```text
Strong password
```

Indata 2:

```text
salasana123
```

Utskrift 2:

```text
Weak password
```

Indata 3:

```text
Lyhyt1a
```

Utskrift 3:

```text
Weak password
```

### Arbetssätt

Skriv lösningen i filen `main.py`. Testa programmet med exempelindata med kommandot `python3 main.py`, gör en commit när en del fungerar och pusha den senaste versionen till GitHub före inlämningstiden.

## In English: Password Strength Checker

### Task

Write a program that reads a password and uses a loop and string methods to check whether it is strong. A password is strong when it meets all four conditions: at least 8 characters, at least one uppercase letter, at least one lowercase letter and at least one digit.

### Input

One line: the password.

### Output

Exactly `Strong password` or `Weak password`.

### Examples

Input 1:

```text
Salasana123
```

Output 1:

```text
Strong password
```

Input 2:

```text
salasana123
```

Output 2:

```text
Weak password
```

Input 3:

```text
Lyhyt1a
```

Output 3:

```text
Weak password
```

### How to work

Write your solution in `main.py`. Test the program with the example inputs using `python3 main.py`, commit whenever a part works, and push the latest version to GitHub before the due date.
