## Exercices en Ruby -- Édition RSpec 3
### Instructions
Fork ce dépôt (repo)
Clone ta version du dépôt sur ta machine locale
Sur ta machine locale, fais un cd dans le dossier racine de ce dépôt dans ton terminal
Tu devras avoir RSpec installé pour que cela fonctionne, alors fais $ gem install rspec si ce n'est pas encore le cas
Concept
Ce dossier est rempli de petits exercices que tu devras réaliser. Ces exercices suivent une approche "Test Driven" (conduite par les tests), ce qui signifie que les fichiers de test sont déjà écrits, et tu devras écrire des programmes qui font passer les tests. Tout d'abord, tu travailleras avec lib/00_hello.rb, puis ce sera lib/01_temperature.rb, et ainsi de suite.

### Démarrage des exercices
Il y a 7 fichiers de test, chacun de ces fichiers concerne un fichier Ruby. Le premier fichier existe (lib/00_hello.rb), les autres n'existent pas encore (01_temperature.rb, etc). Tu devras les créer. Mais commençons d'abord avec le premier programme.

Le premier programme
Si tu exécutes $ rspec spec/00_hello_spec.rb, le programme te dira qu'il s'attend à ce que la méthode hello renvoie "Hello!", mais elle renvoie nil à la place. Va dans le fichier lib/00_hello.rb et tu verras que la méthode hello est vide. Écris donc à l'intérieur de la méthode pour la faire fonctionner !

Fais de même avec greet(name).

### Les autres programmes
Ensuite, tu devras faire fonctionner le fichier de test spec/01_temperature_spec.rb. Si tu exécutes $ rspec spec/01_temperature_spec.rb, le programme te donnera une erreur disant que le fichier lib/01_temperature.rb n'existe pas. Crée-le et relance les tests. Fais fonctionner les tests et passe au programme suivant. Et ainsi de suite.

En gros, c'est du "développement basé sur les erreurs"... tu continueras d'exécuter des tests, en rencontrant des messages d'erreur, en corrigeant ces messages, en exécutant plus de tests... Cela vise non seulement à tester tes compétences en Ruby, mais aussi à te familiariser avec les traces d'erreur et les messages d'erreur qui peuvent sembler compliqués. La plupart du développement que tu feras au début sera exactement comme cela. En fait, la plupart du développement en général est basé sur les erreurs. Alors habitue-toi à cela !

Résolution des problèmes
N'utilise pas d'espaces dans les noms de tes dossiers ! Cela te causera des messages d'erreur terriblement frustrants et le code n'aime pas gérer les espaces. Par exemple :

#### MAUVAIS :
/Documents/My Homework/ruby

#### BON :
/Documents/my_homework/ruby
Crédits
Ceci est un fork de https://github.com/alexch/learn_ruby, créé à l'origine par son auteur.
