# Optimisez la gestion des données d'une boutique avec Python

Projet de rapprochement de deux BDD pour une meilleure analyse des données d’une boutique en ligne.

**(Find English translation below).**

## Mission

Données provenant de la boutique en ligne et du CMS de BottleNeck, un marchand de vin très prestigieux.

Rapprochement de deux exports :
  * Un export de l’ERP avec les références produit, les prix et l'état de stock.
  * Un export d’une table du CMS avec les informations sur les produits commercialisés en ligne (nom, description, nombre de ventes, etc.)

Il existe un Excel avec les liens entre les références du produit dans l’ERP (product_id) et la référence du même produit sur la boutique (SKU).
  * La liste des product_id est exhaustive, mais non-exhaustive pour les références côté web.
  * La colonne id_web du fichier correspond au SKU des produits dans la boutique en ligne.

Suite à cette fusion, BottleNeck a besoin de connaître :
 * Le chiffre d’affaires par produit.
 * Le chiffre d’affaires total.
      
L'entreprise veut également vérifier d'éventuelles erreurs de saisie dans certains prix de produits.
  
## Compétences évaluées

* Gérer les erreurs et les incohérences présentes sur des données stockées,
* Classifier différents types de données,
* Réaliser une analyse univariée pour interpréter des données.

## Livrable

Le notebook Jupyter.


.


# Optimizing store data management with Python
Project to merge two databases to improve data analysis for an online store.

## Mission

Data from the online store and CMS of BottleNeck, a very prestigious wine shop.

Rapprochement de deux exports :
  * An ERP export with product references, prices and stock status.
  * An export from a CMS table with information on products sold online (name, description, number of sales, etc.).

There is an Excel file with linkages between product references in the ERP (product_id) and the reference for the same product in the store (SKU).
  * The product_id listing is exhaustive, but not exhaustive for web references.
  * The file's id_web column corresponds to the product SKU in the online store.

Following this merger, BottleNeck needs to know :
 * Sales per product.
 * Total sales.
      
The company also wants to check for any input errors in certain product prices.
  
## Skills assessed

* Handle errors and inconsistencies in stored data,
* Sort different types of data,
* Perform univariate analysis to interpret data.

## Deliverables

The Jupyter notebook.
