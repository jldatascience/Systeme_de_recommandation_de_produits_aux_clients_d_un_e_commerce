# Systeme_de_recommandation_de_produits_aux_clients_d_un_e_commerce
Proposer à chaque client un produit basé sur son panier d'achat actuel qui maximise la probabilité d'achat.



## Contexte

Un tel système sert à la fois les intérêts du client et ceux de l'entreprise.

Pour les clients : il leur permet de trouver plus facilement les produits qui les intéressent. Leur recherche du prochain produit à acheter est facilitée, et leur expérience d'utilisateur s'en trouve considérablement améliorée. Les clients sont donc plus satisfaits.

Pour l'entreprise : En ce qui concerne l'entreprise, un moteur de recommandation permet d'améliorer la fidélité de ses clients. Comme ils sont satisfaits des produits qu'ils achètent, ils sont plus enclins à collaborer avec l'entreprise. Le taux de désabonnement diminue, ce qui permet à l'entreprise de réduire ses coûts liés à l'acquisition de nouveaux clients. Et bien sûr, l'entreprise voit son chiffre d'affaires augmenter avec la proposition de nouveaux produits aux clients grâce à la vente croisée.




## Objectif

L'objectif du système est :

- d'anticiper les besoins des clients d'une boutique en ligne en développant un système de recommandation.

- de proposer à chaque client un produit basé sur son panier d'achat actuel qui maximise la probabilité d'achat.

La table finale est composée des identifiants du client associés au produit qui lui est proposé et à la probabilité d'achat associée.




## Dataset

Le moteur de recommandation développé est donc basé sur un ensemble de données publiques proposé par The UCI Machine Learning Repository.

Ce jeu de données contient l'historique des transactions d'une boutique en ligne sur 1 an, effectuées entre le 01/12/2010 et le 09/12/2011 pour un commerce de détail en ligne basé au Royaume-Uni.
L'entreprise vend principalement des cadeaux uniques pour toutes les occasions. De nombreux clients de l'entreprise sont des grossistes.





## Démarche

Cf. le notebook ci-joint.

La création de ce système de recommandation sur les données du commerce électronique s'est faite via l'algorithme "Fp Growth" qui est un modèle de Data Mining basé sur des règles d'association.



## Conclusion

Parmi un catalogue de produits de plus de 3000 articles, notre modèle simple basé sur des règles d'association permet de prédire dans 36% des cas le prochain produit que le client achètera et donc de générer des revenus supplémentaires significatifs.

L'avantage de ce modèle est qu'il offre une très bonne précision tout en étant à la fois facile à mettre en œuvre et explicable.

En effet, contrairement à d'autres modèles d'intelligence artificielle qui peuvent apparaître comme des "boîtes noires" parce qu'ils sont difficiles à expliquer, les résultats du modèle Fp Growth sont compréhensibles parce que vous y trouverez toutes les règles spécifiques à votre entreprise.




