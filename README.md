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

