# dartTPdartContact
# Gestion de contact 
1) définir une classe Contact(name,surname,addressLine1,addressLine2,_email,_mobileTel,_homeTel)
homeTel et addressLine2 peuvent être null (définir un constructeur simple et un constructeur sans addressLine2 et _homeTel)
2)ajouter un get nameSurname qui retourne une chaine contenant le name et le surname.
3) ajouter un get address qui retourne addressLine1 et addressLine2 concatinées
4) ajouter une méthode privée validateEmail(email) qui teste si un email est valide ou non
5) ajouter 2 méthodes privées validateMobileTel(mobileTel) et validatehomeTel(homeTel )
6) ajouter un set email qui permet de modifier l'email avec un email valide
7) ajouter les setters mobileTel et homeTel
8) définir une Classe ListContact(List<Contact> listContact)
9) définir la méthode addContact qui permet d'ajouter un contact à la liste de contact
10) définir la méthode deleteContact qui permet de supprimer un contact de la liste de contacts
11) définir searchContact(String contact) qui cherche et retourne tous les contacts contenant une chaine quelconque contact
