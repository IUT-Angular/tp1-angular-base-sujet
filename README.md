# Sujet du TP1

1. Création d'une application Angular via la CLI
2. Mise en place d'un modèle en TypeSript `Book`
  - composé d'un `id` (type `number`), `title` (type `string`), `author` (type `string`), `publicationDate` (type `Datetime`)
3. Mise en place d'un stub JSON contenant 3 livres
4. Création d'un service `BookService`
  - qui chargera dans une propriété `books: Book[]` les livres issues du stub JSON
  - qui contiendra une méthode `getAll(): Book[]`
5. Création d'un composant `book-list` qui affichera l'ensemble des livres
6. BONUS : création d'un composant `book-form` permetant d'ajouter un formulaire dans la liste des livres présents dans le service

A noter, que pour la création des composants il n'est pas nécessaire de générer le fichier `.spec.ts` ni le fichier `.css` ou `.scss`
