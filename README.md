# 2023-2024 E3 Startup

# Contexte général
Une nouvelle startup, `InnovateTech`, gère ses projets et ses employés de manière très structurée pour assurer une croissance rapide et efficace. Vous devez créer un système en Java pour gérer les employés, les projets et les affectations.


## ATTENTION
Commencez par lire cette consigne `avec grande attention` et prenez garde :

- Les descriptions fonctionnelles sont précises et le choix des mots n'est pas anodin.
- Faites les points mentionnés avec précision et dans l'ordre indiqué.
- Revérifiez bien ensuite avoir fait ce qui est demandé.

# Consigne
### Employés
Dans le package `models`, créez une classe nommée `Employe`. Un `Employe` aura plusieurs caractéristiques : le `nom`, le `prenom`, le `poste` (Ex: CEO, CTO, CFO, Développeur) et le `salaire`. Par exemple, un employé peut s'appeler Marie Dupont, occuper le poste de Développeur, et avoir un salaire de `50'000.0 CHF`. Toutes ces informations doivent être fournies lors de la création de l'employé. Il doit être possible de demander toutes ces informations à un employé, mais elles ne pourront pas être modifiées après coup. Lorsqu'on affiche un employé, celui-ci doit se présenter sous la forme : "DUPONT Marie (Développeur) [50'000.00 CHF]".

### Projets
Toujours dans le package `models`, créez une classe nommée `Projet`. Un `Projet` aura plusieurs caractéristiques : son `nom`, le `budget', la `date de fin` et une liste d'employés. Par exemple, un projet peut s'appeler "Projet Alpha", avoir un budget de `150'000.0 CHF`, et une date de fin fixée au 31 décembre 2024. Toutes ces informations doivent être fournies lors de la création du projet, sauf la liste des employés, qui sera initialement vide. Il doit être possible de demander toutes ces informations à un projet. Le nom, le budget et la deadline ne pourront pas être modifiés après coup. On doit pouvoir ajouter et retirer des employés d'un projet, et demander la liste des employés affectés à un projet. Lorsqu'on affiche un projet, celui-ci doit se présenter sous la forme : "Projet: Projet Alpha, Budget: 150000.00 EUR, Deadline: 2024-12-31, Employes: [Marie Dupont, Jean Martin]".

### Startup
Dans le package `models`, créez une classe nommée `Startup`. Une `Startup` aura plusieurs caractéristiques : le nom, une liste d'employés et une liste de projets. Par exemple, la startup peut s'appeler "InnovateTech". Le nom de la startup doit être fourni lors de la création. Les listes d'employés et de projets seront initialement vides. Il doit être possible d'ajouter et de retirer des employés et des projets de la startup. On doit pouvoir affecter un employé à un projet spécifique de la startup, et retirer un employé d'un projet. On doit également pouvoir demander la liste des employés et des projets de la startup.

### Application
Dans le `main()` de la classe `Application`, vous devez effectuer plusieurs opérations. D'abord, créez une nouvelle startup nommée "InnovateTech". Ensuite, ajoutez les employés suivants : Marie Dupont, Développeur, avec un salaire de 50 000.0 EUR, et Jean Martin, Manager, avec un salaire de 60 000.0 EUR. Ajoutez ensuite les projets suivants : "Projet Alpha", avec un budget de 150 000.0 EUR et une deadline fixée au 31 décembre 2024, et "Projet Beta", avec un budget de 100 000.0 EUR et une deadline fixée au 30 novembre 2023. Affectez les employés aux projets comme suit : Marie Dupont au Projet Alpha et Jean Martin au Projet Beta. Enfin, affichez les détails de la startup, de ses employés et de ses projets, ainsi que les affectations.

### Exemple de résultat sur la console
Si vous avez correctement réalisé cette application, vous devriez obtenir un affichage ressemblant à ceci :

```
Startup: InnovateTech
Employes:
- Employe: Marie Dupont, Poste: Développeur, Salaire: 50000.00 EUR
- Employe: Jean Martin, Poste: Manager, Salaire: 60000.00 EUR
Projets:
- Projet: Projet Alpha, Budget: 150000.00 EUR, Deadline: 2024-12-31, Employes: [Marie Dupont]
- Projet: Projet Beta, Budget: 100000.00 EUR, Deadline: 2023-11-30, Employes: [Jean Martin]
```

### Remise
Faites signe au professeur lorsque vous aurez terminé et que vous êtes prêt à rendre. Il vous autorisera à remettre le réseau. Rendez votre travail par push GitHub et quittez rapidement la salle en silence.

---

J'espère que cet exercice vous aidera à mieux comprendre la gestion des startups et des projets en Java. Bon travail !
