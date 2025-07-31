# Microserviciu matematic Flask

## Descriere

Acest proiect implementează un microserviciu REST (Flask) ce oferă API pentru:

- Ridicare la putere (`/api/pow`)
- Calcul Fibonacci (`/api/fibonacci`)
- Calcul factorial (`/api/factorial`)

Toate request-urile sunt logate într-o bază de date SQLite. Structura respectă pattern-ul MVC/MVCS, folosește Pydantic pentru validare și serializare, și este lintat cu flake8.

## Rulare locală

1. Instalează dependențele:
   ```
   pip install -r requirements.txt
   ```
2. Rulează aplicația:
   ```
   python -m app.main
   ```

## Structură directoare

- `app/controllers` - rute Flask
- `app/services` - logică business
- `app/models` - modele interne
- `app/schemas` - Pydantic
- `app/db` - conexiune DB

## Extensii opționale (urmează să fie adăugate):

- Docker, caching, monitorizare, autentificare, logging, worker async, CLI.

## Autori

- Exemplu: Nume1, Nume2, Nume3
