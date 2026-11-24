Table user
- nom
- mot de passe 
- budget

Table typeDestinataire
- id
- libelle

Table occasion
- id
- libelle

Table categorie
- id 
- libelle

Table cadeau 
- id 
- libelle
- photo
- idcategorie
- idoccasion
- idTypeDest
- prix
- lieu de vente
- description
- note(moyenne)

Moyenne = somme de note / nb de note

ex : 3 utilisateur notent : 2,3 et 4 

note = 2+3+4/3

Table wishList
- id
- idUser
- idcadeau


Table historique
- id
- idUser
- date
- idcadeau