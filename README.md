# Optimisez la gestion des données d'une boutique avec Python
Projet de rapprochement de deux BDD pour une meilleure analyse des données d’une boutique en ligne.

## Mission

Données provenant de la boutique en ligne et du CMS de BottleNeck, un marchand de vin très prestigieux.

1. Rapprochement de deux exports :
  * Un export de l’ERP avec les références produit, les prix et l'état de stock.
  * Un export d’une table du CMS avec les informations sur les produits commercialisés en lignes (nom, description, nombre de ventes, etc.)

Il existe un Excel avec les liens entre les références du produit dans l’ERP (product_id) et la référence du même produit sur la boutique (SKU).
  * La liste des product_id est exhaustive, mais non-exhaustive pour les références côté web.
  * La colonne id_web du fichier correspond au SKU des produits dans la boutique en ligne.

2. Suite à cette fusion, BottleNeck a besoin de connaître :
 * Le chiffre d’affaires par produit
 * Le chiffre d’affaires total
      
4. L'entreprise veut également vérifier d'éventuelles erreurs de saisie dans certains prix de produits.
  
## Compétences évaluées

* Gérer les erreurs et les incohérences présentes sur des données stockées
* Classifier différents types de données
* Réaliser une analyse univariée pour interpréter des données

## Livrable

Le notebook Jupyter.
