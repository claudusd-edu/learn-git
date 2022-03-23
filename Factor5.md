# V. Assemblez, publiez, exécutez
## Séparez strictement les étapes d’assemblage et d’exécution
Une base de code est transformée en un déploiement (non-développement) à  travers les étapes suivantes :

L’étape d’assemblage (ou “build”) est une transformation qui convertit un dépôt de code en un paquet autonome exécutable appelé l’assemblage (ou “build”). En utilisant une version du code référencée par un commit spécifié lors du processus de déploiement, l’étape d’assemblage va chercher toutes les dépendances externes et compile les fichiers binaires et les ressources.
L’étape de publication (ou “release”) prend l’assemblage produit à l’étape précédente et le combine avec la configuration de déploiement courante. La release résultante contient à la fois l’assemblage et la configuration, et elle est prête pour une exécution immédiate dans l’environnement d’exécution.
L’étape d’exécution (ou “runtime”) fait fonctionner l’application dans l’environnement d’exécution, en lançant un ensemble de processus de l’application associée à la release considérée.

(Et Factor5, c'est aussi un studio amateur allemand des années 80 qui faisait des trucs cools sur Amiga, c'était la minute culture)