# API Produits

## Aperçu
Ce projet est une API basée sur Symfony pour la gestion des produits. Il prend en charge les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) et est conçu pour être testé avec Postman et partagé sur GitHub.

## Points de terminaison de l'API

### GET /api/produits
Récupère tous les produits.

### POST /api/produits
Ajoute un nouveau produit.
Exemple de corps (format JSON) :
```json

{
  "nom": "Produit A",
  "prix": 10.0
}
```
### PUT /api/produits/{id}
Met à jour un produit existant. Exemple de corps (format JSON) :
```json
{
  "nom": "Produit A mis à jour",
  "prix": 15.5
}
```

### DELETE /api/produits/{id}
Supprime un produit.

