# github_actions_demo

![CI](https://github.com/YaredRiveros/github_actions_demo/actions/workflows/devops.yml/badge.svg)
![Release](https://img.shields.io/github/v/release/YaredRiveros/github_actions_demo)

Laboratorio de CI/CD con GitHub Actions y Python.

- `devops.yml`: test (cobertura mínima 80%) → package → docs → deploy a GitHub Pages (con aprobación manual).
- `release.yml`: publica un GitHub Release al subir un tag `v*`.
- Página: https://yaredriveros.github.io/github_actions_demo/

## Uso

```bash
pip install -r requirements.txt
python hello.py
pytest -q
```

## Publicar una versión

```bash
git tag -a v1.0.0 -m "Primera versión estable"
git push origin v1.0.0
```
