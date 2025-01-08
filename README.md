# JAVA LTS Versions

**Latest version**: Java 23

### LTS Java versions:

#### Java 8 (2014)
- Lambda Expressions
- Stream API
- Optional class
- Default and Static Interface Methods

#### Java 11 (2018)
- HTTP Client (Standard)
- String Improvements: isBlank(), strip(): Removes leading and trailing spaces, repeat(), lines(): splits the string into a stream of lines 

#### Java 17 (2021)
- Sealed Classes and Interfaces
- Records

#### Java 21 (2023)
- Virtual Threads
- Foreign Function and Memory API (Incubator)

---

# SOLID PRINCIPLES

Améliorer la lisibilité, flexibilité et maintenabilité de code orienté objet

- **S**: Single Responsibility
- **O**: Open/Closed: ouvert à l’extension, fermé à la modification; ex: au lieu de modifier une classe, créer une sous-classe qui hérite de la classe de base
- **L**: Liskov Substitution: les objets d’une classe dérivée peuvent remplacer ceux de la classe mère sans modifier le comportement attendu. Ex: animal, fly
- **I**: Interface Segregation: Avoir plusieurs interfaces spécifiques est mieux que d’avoir une seule interface générale. Une interface ne doit pas forcer une classe à implémenter des méthodes inutiles.
- **D**: Dependency Inversion: Les modules de haut niveau ne doivent pas dépendre des modules de bas niveau, les deux doivent dépendre des abstractions.

---

# COLLECTIONS API

1. **Collection**:
   - **List**: ArrayList, LinkedList, Vector (ordonné)
   - **Queue**: PriorityQueue, LinkedList, ArrayDeque (pile/file)
   - **Set**: HashSet, TreeSet (non doublons)

2. **Map**: HashMap, TreeMap (clé/valeur)

---

# STREAMS API

Permet de travailler avec des collections d’une manière fonctionnelle et déclarative, gérer facilement des traitements complexes et garder un code propre et maintenable.

- **Operations intermédiaires**: `filter`, `map`, `distinct`, `sorted`
- **Operations terminales**: `collect`, `forEach`, `reduce`, `count`

---

# DESIGN PATTERNS

1. **Creation**: Factory, Singleton, Builder, Prototype
2. **Structure**: Decorator, Proxy, Adapter, Bridge
3. **Comportment**: Strategy, Observer, State, Command

---

# POO en JAVA

### 4. Qu'est-ce que le polymorphisme en Java ?
**Réponse**:  
Le polymorphisme permet à une même méthode ou interface de se comporter de manière différente selon le contexte. Il existe deux types de polymorphisme :
- **Polymorphisme de méthode** (Surcharge et redéfinition):
  - **Surcharge** : Deux méthodes avec le même nom mais des signatures différentes.
  - **Redéfinition** (Override) : Une méthode dans une sous-classe qui remplace la méthode d'une classe parente.
- **Polymorphisme d'objet** : Permet d’utiliser des objets de types différents sous une forme commune, généralement grâce à l'héritage ou à des interfaces.

### 6. Qu'est-ce qu'une exception en Java ?
**Réponse**:  
Une exception en Java est un événement qui perturbe le flux normal d'exécution d'un programme. Les exceptions peuvent être causées par des erreurs comme une division par zéro, un fichier introuvable ou un dépassement de mémoire. Les exceptions peuvent être capturées et traitées grâce aux blocs `try-catch` pour éviter que le programme ne plante.

### 10. Qu'est-ce que la sérialisation en Java ?
**Réponse**:  
La sérialisation est le processus de conversion d'un objet en un flux de bytes afin de le stocker dans un fichier ou de le transmettre sur un réseau. La classe doit implémenter l'interface `Serializable`. Ce processus est inversement appelé **désérialisation**, où les bytes sont reconvertis en objet.

### 12. Qu'est-ce que la programmation fonctionnelle en Java ?
**Réponse**:  
La programmation fonctionnelle en Java, introduite avec Java 8, repose sur des concepts comme les fonctions pures, l'immuabilité, et les expressions lambda. Elle permet d'utiliser des fonctions comme arguments, de retourner des fonctions, et de traiter des collections de manière déclarative (avec des streams).

Lambda est une fonction sans nom qui peut être utilisée comme argument dans une méthode, c’est une manière d’écrire une fonction anonyme.  
L'injection de dépendances est un principe de conception qui permet de dissocier la création des objets de leur utilisation.  
Une interface en Java est un contrat qui définit un ensemble de méthodes que les classes doivent implémenter.
