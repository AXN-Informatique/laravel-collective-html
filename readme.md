# LaravelCollective HTML - Laravel 11/12 Compatible Fork

Ce package est un fork de LaravelCollective HTML, compatible avec Laravel 10, 11 et 12.

## À propos

Le package original LaravelCollective HTML a été abandonné. Ce fork maintient la compatibilité avec les versions récentes de Laravel (10, 11, 12) pour permettre aux applications existantes de continuer à fonctionner lors de leurs mises à jour.

## Compatibilité

- PHP: ^8.1
- Laravel: ^10.0 | ^11.0 | ^12.0

## Installation

### 1. Ajouter le repository dans votre composer.json

Ajoutez ce repository dans la section `repositories` de votre `composer.json` :

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/AXN-Informatique/laravel-collective-html"
        }
    ]
}
```

### 2. Installer le package

```bash
composer require laravelcollective/html
```

## Documentation

La documentation complète est disponible dans le fichier [DOCUMENTATION.md](DOCUMENTATION.md) de ce dépôt.

Vous pouvez également consulter la documentation originale sur le site [LaravelCollective](https://laravelcollective.com/docs) (pour les anciennes versions).
