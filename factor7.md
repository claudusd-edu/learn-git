# 7. Port binding
--
## Définition
Une application respectant le principe des 12 facteurs est auto suffisante. Si elle propose un/des service(s), il est nécessaire qu'elle puisse le faire indépendamment de tout autre service.
* i.e une application déployée sur un serveur ne doit pas avoir besoin d'une autre application sur un autre serveur pour fonctionner.

Les services proposées par une application cloud native sont alors exportées sur un port, pour être utilisé par les autres applications. Cela implique que les outils d'écoute soient implémentés dans les applications, afin qu'elles puissent transmettre et reçevoir ces informations de manière autonome.
* i.e une application web exporte un service HTTP sur un port pré-défini (ex. 80), mis à disposition pour toutes les autres applications qui peuvent en avoir besoin.

En résumé, il est nécessaire de développer des applications qui peuvent être indépendantes, afin d'assurer un fonctionnement continuel du workflow.



