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
- prix
- lieu de vente
- description
- note(moyenne)

Table occasionCadeau
- idoccasion
- idcadeau

Table destCadeau
- iddestinataire
- idcadeau

Table categoriecadeau
- idcategorie
- idcadeau

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