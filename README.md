# DOJO Instance

## Setup

```bash
# Sklonuj ten projekt i framework obok siebie
git clone https://github.com/DOJO-GARDEN/instance-ping-test
git clone https://github.com/DOJO-GARDEN/dojo-way

# Wejdź do projektu i podlinkuj framework
cd instance-ping-test
ln -s ../dojo-way/dojo-core dojo-core

# Uruchom
python dojo-core/api.py
```

## Użycie

```bash
curl -X POST http://localhost:8000/seed
curl http://localhost:8000/instances
```

## Struktura

```
instance-*/
├── seed.yaml           ← konfiguracja instancji
├── dojo-core -> ...    ← symlink do frameworka
└── .spore-instances/   ← generowane (git ignore)
```
