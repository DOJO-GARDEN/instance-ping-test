# DOJO Organism

## Setup

```bash
git clone https://github.com/DOJO-GARDEN/organism-ping-test
git clone https://github.com/DOJO-GARDEN/dojo-way

cd organism-ping-test
ln -s ../dojo-way/dojo-core dojo-core

python dojo-core/api.py
```

## Użycie

```bash
curl -X POST http://localhost:8000/seed
curl http://localhost:8000/instances
```

## Struktura

```
organism-*/
├── seed.yaml       ← DNA/konfiguracja
├── dojo-core/      ← symlink do frameworka
└── .organisms/     ← aktywne organizmy
```
