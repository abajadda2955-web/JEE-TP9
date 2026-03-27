#TP Spring Security - Authentification et Gestion des Rôles
---

##Objectif du TP

Découvrir le fonctionnement fondamental de Spring Security en configurant une authentification en mémoire avec gestion des rôles.


##Technologies utilisées

    Spring Boot 3.3.x

    Spring Security

    Spring Web

    Thymeleaf

    Maven

---

##Captures d'écran

Page de connexion personnalisée

<img width="425" height="494" alt="2" src="https://github.com/user-attachments/assets/c78d051d-c198-4950-bd2c-ca3755a2ce37" />



Page d'accueil

<img width="735" height="320" alt="3" src="https://github.com/user-attachments/assets/5ca5b833-701b-4261-a407-815245b6fd48" />


Espace utilisateur

<img width="731" height="226" alt="5" src="https://github.com/user-attachments/assets/966156aa-afc7-49a4-8a8c-28b1eff3fe45" />


Espace administrateur

<img width="732" height="243" alt="4" src="https://github.com/user-attachments/assets/0cad418e-852e-4faa-bb20-5a05afe7c34f" />

Structure du projet

```
src/main/java/ma/fstg/security/
├── SpringSecurityDemoApplication.java
├── config/
│   └── SecurityConfig.java          # Configuration Spring Security
└── web/
    ├── HomeController.java           # Endpoints de test
    └── LoginController.java          # Affichage page login

src/main/resources/
├── application.properties            # Configuration (port 8082)
└── templates/
    └── login.html                    # Page de connexion personnalisée
```


Fonctionnalités implémentées

    ✅ Authentification en mémoire avec utilisateurs et rôles

    ✅ Protection des URLs selon les rôles

    ✅ Page de connexion personnalisée avec CSS

    ✅ Test des accès avec différents comptes

Auteur

BAJADDA ASMA - TP Spring Security
