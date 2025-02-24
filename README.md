# **Structure du Projet Maven**  

Ce projet est organisé selon une architecture modulaire basée sur Maven.  

### **1️⃣ Création du projet parent**  
Le projet principal agit comme un parent pour les différents modules et gère les dépendances partagées.  

### **2️⃣ Module `services` (métier)**  
Ce module contient la logique métier de l'application.  

### **3️⃣ Module `web`**  
- Implémente une interface web avec **Tomcat 10**.  
- Dans le fichier `pom.xml`, l’option `skip` permet d’ignorer l'exécution de Spring Boot lors de la compilation ou des tests.  

### **4️⃣ Module `batch`**  
- Ce module est un projet **Spring Boot** dédié aux traitements batch.  

![Screenshot 2025-02-23 201101](https://github.com/user-attachments/assets/e430cdad-4f47-43d8-8b2d-7ec35c0db010)

Auteur

👤 Seynabou SOUMARE 📧 seynabou@groupeisi.com
