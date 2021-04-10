# Simple MVC

#Mise en place de Twig
Dans le fichier /src/Controller/HomeController.php, ajoute une nouvelle méthode d'action showProducts() comportant l'initialisation du tableau ci-dessous : $products = ['guitare', 'bass', 'bonjo', 'cithare', 'lyre']; Tu peux changer le nom des produits si tu te sens inspiré ;-)

Crée une vue products.html.twig dans le dossier src/View/Home/, reprenant une structure HTML de base Depuis ta nouvelle méthode d'action de ton controller appelle ton fichier en products.html.twig en lui passant ton tableau $products via l’appel à la méthode render() de l'objet $this->twig. Dans cette vue, en utilisant la syntaxe de Twig, tu dois boucler sur le tableau et afficher les produits dans des blocs distincts, à raison de 3 articles par ligne. Puis sous la liste des produits, affiche le resultat d'un dump() du tableau de produit que tu as envoyé à ta page Twig. Envoie le résultat sur un dépôt GitHub et poste le lien en solution
