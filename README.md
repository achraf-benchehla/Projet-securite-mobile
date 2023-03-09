# Projet securite mobile 




Introduction
Les applications de trading sont largement utilisées dans le monde de la finance pour acheter et vendre des actions, des devises et d'autres instruments financiers
. La sécurité de ces applications est cruciale pour garantir l'intégrité des transactions financières et protéger les données sensibles des utilisateurs. Dans ce rapport
, nous présentons une analyse dynamique et statique d'une application de trading pour évaluer sa sécurité en utilisant les outils jadx, le fichier manifest.xml 
et Burp Suite.

Analyse dynamique en utilisant Burp Suite
L'analyse dynamique en utilisant Burp Suite consiste à intercepter le trafic HTTP/S généré par l'application de trading pour détecter les vulnérabilités liées aux
communications réseau. Nous avons utilisé Burp Suite pour effectuer les actions suivantes :

Analyse des requêtes et réponses : Nous avons intercepté les requêtes et réponses échangées entre l'application de trading et le serveur distant pour détecter 
les vulnérabilités liées aux communications réseau, telles que les attaques par injection SQL ou les failles de sécurité XSS.
Analyse de la gestion des sessions : Nous avons vérifié la gestion des sessions de l'application pour éviter les vulnérabilités liées à la gestion des sessions
, telles que les attaques par contournement d'authentification.
Analyse des cookies : Nous avons vérifié la sécurité des cookies utilisés par l'application pour éviter les attaques par détournement 
de session ou les vulnérabilités liées aux cookies.
Les résultats de l'analyse dynamique en utilisant Burp Suite ont montré que l'application de trading était résistante aux attaques communes.
Cependant, nous avons identifié une vulnérabilité liée à la gestion des sessions, qui a été corrigée dans la version suivante de l'application.

Analyse statique en utilisant jadx et le fichier manifest.xml
L'analyse statique en utilisant jadx et le fichier manifest.xml consiste à examiner le code source de l'application sans l'exécuter. 
Nous avons utilisé les outils jadx et le fichier manifest.xml pour effectuer les actions suivantes :

Analyse de la sécurité du code : Nous avons examiné le code source de l'application pour détecter les vulnérabilités de sécurité, telles que les injections SQL,
les failles de sécurité XSS et les vulnérabilités de contournement d'authentification.
Analyse de la qualité du code : Nous avons évalué la qualité du code source de l'application en utilisant des métriques de complexité, de duplication de code et
de cohérence.
Les résultats de l'analyse statique en utilisant jadx et le fichier manifest.xml ont montré que le code source de l'application était bien structuré et ne présentait
aucune vulnérabilité de sécurité majeure. Cependant, nous avons identifié quelques améliorations possibles en termes de qualité du code, telles que la réduction de
la duplication de code et l'amélioration de la cohérence.

Conclusion
Dans ce rapport, nous avons présenté une analyse dynamique et statique d'une application de trading pour évaluer sa sécurité. L'analyse dynamique a été réalisée
en utilisant Burp Suite pour détecter les vulnérabilités liées aux communications réseau, tandis que l'analyse statique a été réalisée en utilisant les outils 
jadx et le fichier manifest.xml pour examiner le code source de l'application.

Les résultats de l'analyse dynamique ont montré que l'application de trading était résistante aux attaques communes, mais qu'une vulnérabilité liée à la gestion
des sessions a été identifiée et corrigée dans la version suivante de l'application. Les résultats de l'analyse statique ont montré que le code source de 
l'application était bien structuré et ne présentait aucune vulnérabilité de sécurité majeure, mais qu'il y avait des améliorations possibles en termes de qualité
du code.

En conclusion, cette analyse dynamique et statique a permis d'évaluer la sécurité de l'application de trading et d'identifier des améliorations possibles pour garanti
r la sécurité des transactions financières et protéger les données sensibles des utilisateurs.
