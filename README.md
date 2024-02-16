# quest-twig

Hello Wilder !

If you are here, it's certainly because you start the quests about Twig !

So, use me as a template, and follow instructions on Odyssey !

Enjoy your journey !

branch 0001 twig :
CHALLENGE 

    Dans un nouveau fichier /public/products.php, ajoute l'initialisation du tableau ci-dessous :

$products = ['guitare', 'bass', 'bonjo', 'cithare', 'lyre', 'harpe'];

Tu peux changer le nom des produits si tu te sens inspiré ;-)

    Crée une vue products.html.twig dans le dossier src/View/, reprenant une structure HTML de base.
    Depuis ton nouveau fichier products.php appelle ton template products.html.twig en lui passant ton tableau $products via l’appel à la méthode render() de l'objet $twig.
    Dans cette vue, en utilisant la syntaxe de Twig, tu dois boucler sur le tableau et afficher les produits dans une liste HTML.
    Puis sous la liste des produits, affiche le resultat d'un dump() du tableau de produit que tu as envoyé à ta page Twig.
    Envoie le résultat sur un dépôt GitHub et poste le lien en solution

branch 0002 twig :
CHALLENGE
    Héritage et inclusion

    Commence par créer le fichier src/View/layout.html.twig avec le code suivant : VOIR LAYOUT.HTML.TWIG
    
    Un fois le fichier créé, modifie ce layout pour avoir un title par défaut
    Crées une page src/View/home.html.twig qui hérite du layout.html.twig
    Cette page utilisera le titre parent et ajoutera "- Accueil"
    Créé un composant pour une navbar (ne t’embête pas avec la mise en forme pour cette quête) et inclus le dans ton fichier layout.html.twig
    Envoie le résultat sur ton dépôt GitHub et poste le lien en solution

Critères de validation

    Pour corriger, clone le projet et pense à lancer un composer install. Le dossier vendor ne doit pas être inclus dans le versionnage sous git.

    parent() est utilisé dans le fichier home.html.twig

    Les bonnes pratiques de nommage sont appliquées

branch 00031twig
CHALLENGE 
    
    Ajouter un email de contact dans un pied de page

    Pour ce challenge tu repartiras du dépôt Github que tu as déjà utilisé lors de la quête précédente : https://github.com/WildCodeSchool/quest-twig

    Commence par créer le fichier src/View/_footer.html.twig avec le code suivant : VOIR FICHIER FOOTER
    </footer>

    Ensuite, rends toi dans le fichier 'src/View/layout.html.twig' que tu as créé lors de la quête précédente et inclus le footer dans la balise body, juste aprés le block content
    Va ensuite ajouter une globale comme dans l'exemple montré plus haut dans le fichier config/twig.php. Stocke dans cette globale une adresse email
    Vérifie que sur ta page tu as maintenant bien un footer avec une adresse email de contact 🤓
    Crée ensuite dans public un fichier details.php qui appelle une vue details.html.twig (que tu dois créer) et qui héritera de layout.html.twig
    Vérifie que sur cette nouvelle page aussi tu as bien l'email qui apparait 🤓🤓
    Envoie le résultat sur ton dépôt GitHub et poste le lien en solution

Critères de validation

    Pour corriger, clone le projet et pense à lancer un composer install si ce n'est pas déjà fait.

    Il y a bien un $twig->addGlobal() dans config/twig.php pour déclarer un email de contact

    Il y a bien l'inclusion du fichier src/View/_footer.html.twig dans le layout.html.twig

    Le dossier vendor de ton projet n'est pas versionné sous git.



