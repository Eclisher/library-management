# Answers to questions in TD2

2.  ### b.i) Pourquoi UpdateBookAuthor possède uniquement l’identifiant de CrupdateBook et l’identifiant de Author, mais sans les autres propriétés telles que bookName et authorName comme dans leur composant respectif ? 

La raison pour laquelle UpdateBookAuthor ne possède que l'ID de CrupdateBook et l'ID de Author est qu'il est destiné à être utilisé pour la mise à jour de la relation entre livre et auteur, et aussi que bookName et authorName ne sont pas nécessaire dans cette opération

### b.ii.Dans quel cas, UpdateBookAuthor devrait avoir les propriétés de CrupdateBook et de Author ?

UpdateBookAuthor devrait avoir les propriétés de CrupdateBook et de Author dans le cas où on a besoins les informations du livre et d'auteur