# Answers

Nom : AKHERRAZ
Prénom : Brahim
NB : 4

# 1.
A quoi sert l'A/B testing ?
deploiement sur une partie de la population et permets de tester
Comment appliquer de l'A/B testing grâce à Istio ?
avec une regles qui va basculer de la v1 a la v2
# 2.
Comment simuler un problème de timeout avec Istio ?
on peut simuler un probleme via un falt injection
Comment le résoudre ?on peut configurer le délai maximum 

# 3.
Qu'est-ce que le canary release ?
le canary release est une technique qui réduit le risque d'avoir des problèmes en production
En quoi est-ce utile ?
Cette technique sert a ne pas impacter tous les utilisateurs
Comment l'implémenter dans Istio ?
on établit des regles comme pour le A/B testing
# 4.

# 5.
Qu'est-ce qu'un Circuit Breaker ?
un circuit breaker permet de load balancer des flux.
Comment l'implémenter dans un contexte Kubernetes ? on peu crée une regle

# 6.
Pourquoi avoir besoin de mirrorer le traffic vers un autre composant ?
le mirror permet de rerouter vers un autre composant pour proteger la production. Ainsi, la production est protégé lors du deploiment d'une version.

# 7.
Pourquoi bloquer le traffic vers un service ?
bloquer un service permet de ne pas ralentir tous les services disponibles.

Comment l'implémenter simplement avec Istio ?
mettre le rate limit à 0

# 8.
Quel est la problématique de tracing distribué ?
le tracing permet de voir le comportement des application d'une version deployé. 

Quel est la spécification du tracing distribué et son implémentation dans Istio ?
Jaeger est une orchestrateur des tracing
# 9.
Comment s'appelle l'outil de récupération des métrics ?
l'outil de recuperation des metrics s'appelle Prometheus

# 10.

# 11.
Comment s'appelle l'outil de visualisation des métrics ?
l'outil de visualition des métrics s'appelle Grafana

# 12.
A quoi sert un servicegraph ?
servicegraph permet de voir l'ensemble des services sous forme de schéma 

Quel serait l'utilité dans le quotidien d'un ops ? ca permets de voir un probleme s'il y en a simplement et ainsi de garantir la continuité du service 
