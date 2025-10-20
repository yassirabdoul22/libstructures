# 📚 Structures de Données en C

Ce document présente les structures de données classiques en C : **Linked List**, **Double Linked List**, et **Map**.  
Il inclut des exemples de code, des diagrammes et des exercices pratiques.

---

## 1️⃣ Linked List (Liste Chaînée Simple)

Une **linked list** est une suite d’éléments (nodes) où chaque élément contient une donnée et un pointeur vers le suivant.

### Structure

```c
typedef struct s_node {
    int data;
    struct s_node *next;
} t_node;
