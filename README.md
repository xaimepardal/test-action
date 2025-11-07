# Git Bisect Ejercicio

## Práctica de git blame / bisect

Autores simulados:
- Alice
- Bob
- Carol
- Dave


## Tests:

```
pytest -v
``` 

Ejecutar test sobre un fichero:

```
pytest -v tests/test_division.py 
```

## Logs

```
git log --oneline
```

## Bisect

```
git bisect start
git bisect bad HEAD
git bisect good 6ba9e0f
```