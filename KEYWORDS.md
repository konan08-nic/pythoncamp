# La liste des mots clés pour le langage Python v3.X

![Table des Mots Cles en Python](https://github.com/konan08-nic/pythoncamp/blob/main/assets/py-mots-cles.png)

> **Note**: Les mots avec **'*'** ne sont plus des mots-clés en Python 3 mais des fonctions du module builtins.

# Table des mots clefs avec description

<table style="margin:0.5em auto 0.5em auto; border-collapse:collapse; padding:0.5em;">
<tbody>
  <tr>
    <th>Mot</th>
    <th>Définition</th>
  </tr>
  <tr>
    <td>and</td>
    <td>Opérateur ET booléen logique</td>
  </tr>
  <tr>
    <td>as</td>
    <td>mot clef pour les alias</td>
  </tr>
  <tr>
    <td>assert</td>
    <td></td>
  </tr>
  <tr>
    <td>break</td>
    <td>Sortie de boucle</td>
  </tr>
  <tr>
    <td>class</td>
    <td>
      Définition de classe d'objet (<a href="https://fr.wikipedia.org/wiki/POO" class="extiw" title="w:POO" target="_blank"> Programmation Orientée Objet</a>)
    </td>
  </tr>
  <tr>
    <td>continue</td>
    <td>Countiuer ou reprendre la boucle sans executer le reste du code</td>
  </tr>
  <tr>
    <td>def</td>
    <td>Définition de fonction</td>
  </tr>
  <tr>
    <td>del</td>
    <td>Suppression de</td>
  </tr>
  <tr>
    <td>elif</td>
    <td>Condition contraire</td>
  </tr>
  <tr>
    <td>else</td>
    <td>Contraire</td>
  </tr>
  <tr>
    <td>except</td>
    <td>Sauf (à utiliser après "try")</td>
  </tr>
  <tr>
    <td>exec</td>
    <td>exécuter</td>
  </tr>
  <tr>
    <td>finally</td>
    <td>fillanlement, permet d'exécuter un bloque de code en cas d'exception</td>
  </tr>
<tr>
  <td>for</td>
  <td>Boucle</td>
  </tr>
  <tr>
    <td>from</td>
    <td>De</td>
  </tr>
  <tr>
    <td>global</td>
    <td>Définition (ou utilisation) dans une fonction d'une variable globale</td>
  </tr>
  <tr>
    <td>if</td>
    <td>Condition</td>
  </tr>
  <tr>
    <td>import</td>
    <td>Importation de module</td>
  </tr>
  <tr>
    <td>in</td>
    <td>Contient</td>
  </tr>
  <tr>
    <td>is</td>
    <td>Est</td>
  </tr>
  <tr>
    <td>is not</td>
    <td>N'est pas</td>
  </tr>
  <tr>
    <td>lambda</td>
    <td>Définition d'une fonction Lambda</td>
  </tr>
  <tr>
    <td>not</td>
    <td>Négation logique</td>
  </tr>
  <tr>
    <td>or</td>
    <td>Opérateur de choix OU booléen logique</td>
  </tr>
  <tr>
    <td>pass</td>
    <td>passer ou sauter un block de code</td>
  </tr>
  <tr>
    <td>print</td>
    <td>Afficher</td>
  </tr>
  <tr>
    <td>raise</td>
    <td>Permet de lancer une exception</td>
  </tr>
  <tr>
    <td>return</td>
    <td>Stopper la fonction courante ( et renvoyer sa valeur)</td>
  </tr>
  <tr>
    <td>sort</td>
    <td>Classer par ordre alphabétique</td>
  </tr>
  <tr>
    <td>try</td>
    <td>Essayer (généralement suivi de "except"&nbsp;: sauf)</td>
  </tr>
  <tr>
    <td>while</td>
    <td>Boucle</td>
  </tr>
  <tr>
    <td>yield</td>
    <td>S'emploie uniquement dans une fonction, et renvoie son résultat régénéré</td>
  </tr>
  </tbody>
</table>

# Les Fonctions Usuelles

<table style="margin:0.5em auto 0.5em auto; border-collapse:collapse; padding:0.5em;">
<tbody><tr>
<th>Commande
</th>
<th>Définition
</th></tr>
<tr>
<td>help()</td>
<td>Affiche l'aide sur le paramètre
</td></tr>
<tr>
<td>dir()</td>
<td>Affiche les méthodes du paramètre
</td></tr>
<tr>
<td>print()</td>
<td>Affiche le texte en paramètre
</td></tr>
<tr>
<td>input()</td>
<td>Enregistre la saisie de l'utilisateur
</td></tr>
<tr>
<td>raw_input()</td>
<td>Équivalent à input() (sous Python 3, préférer input())
</td></tr>
<tr>
<td>len()</td>
<td>Renvoie la taille du paramètre
</td></tr>
<tr>
<td>range()</td>
<td>Affiche la liste des entiers de l'intervalle du paramètre
</td></tr>
<tr>
<td>ord()</td>
<td>Renvoie l'ordinal associé au caractère en paramètre
</td></tr>
<tr>
<td>locals()</td>
<td>Créer un dictionnaire (objet "dict"), dont le contenu est accessible avec "[]"
</td></tr>
<tr>
<td>globals()</td>
<td>Comme locals() mais en incluant les variables globales
</td></tr>
<tr>
<td>str()</td>
<td>Convertit une variable en caractères
</td></tr>
<tr>
<td>int()</td>
<td>Convertit une variable en nombre entier
</td></tr>
<tr>
<th colspan="2">Fichiers
</th></tr>
<tr>
<td>open()</td>
<td>Ouvrir un fichier
</td></tr>
<tr>
<td>close()</td>
<td>Fermer un fichier
</td></tr>
<tr>
<td>read()</td>
<td>Lire un fichier
</td></tr>
<tr>
<td>readline()</td>
<td>Lire une ligne
</td></tr>
<tr>
<td>readlines()</td>
<td>Lire les lignes séparées par des "\n,"
</td></tr>
<tr>
<td>tell()</td>
<td>Donne la position d'un objet
</td></tr>
<tr>
<td>seek()</td>
<td>Donne la position d'un objet
</td></tr>
<tr>
<td>write()</td>
<td>Écrire dans un fichier
</td></tr></tbody></table>
