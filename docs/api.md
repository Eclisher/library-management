# Answers to questions in TD2

2.  ### b.i) Pourquoi UpdateBookAuthor possède uniquement l’identifiant de CrupdateBook et l’identifiant de Author, mais sans les autres propriétés telles que bookName et authorName comme dans leur composant respectif ? 

La raison pour laquelle UpdateBookAuthor ne possède que l'ID de CrupdateBook et l'ID de Author est qu'il est destiné à être utilisé pour la mise à jour de la relation entre livre et auteur, et aussi que bookName et authorName ne sont pas nécessaire dans cette opération

### b.ii.Dans quel cas, UpdateBookAuthor devrait avoir les propriétés de CrupdateBook et de Author ?

UpdateBookAuthor devrait avoir les propriétés de CrupdateBook et de Author dans le cas où on a besoins les informations du livre et d'auteur

3. ### Pourquoi les paginations sont-elles nécessaires?
Les paginations sont nécessaires pour: 
- afficher une grande quantité de données de manière ordonnée et efficace.
- la géstion des grands ensembles de données 
- la performance 
- l'éxperience utilisateur (ils peuvent naviguer d'une page à l'autre)   
- la personnalisation 

4. ###  a. Est ce qu’on peut gérer la pagination à travers les entêtes de la requête ? Justifiez votre réponse.
Oui, on peut gérer la pagination à travers les entêtes de la requête. Parce qu'on utilise ___query parameters___  comme:
- __X-Page__ : L'identifiant de la page à renvoyer.
- __X-PageSize__ : Le nombre d'auteurs à renvoyer par page.



### b. Est ce qu’on doit gérer la pagination  à travers les entêtes de la requête ?  Justifiez votre réponse.

Non,il n'est pas nécessaire de  gérer la pagination  à travers les entêtes de la requête. Parce qu'on peut     utiliser _les paramètres URL_ 