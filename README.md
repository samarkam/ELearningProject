# ELearningProjectReactFrontEnd

🎓 StudyNotion - Plateforme E-learning Moderne
StudyNotion est une plateforme e-learning complète et intuitive conçue pour offrir une expérience d’apprentissage engageante, accessible et personnalisée. Développée à des fins éducatives, cette application web permet aux étudiants, enseignants et administrateurs de collaborer autour de contenus pédagogiques.


Objectifs
✅ Accessibilité multiplateforme (PC, tablette, mobile)
✅ Interactivité avec quiz, vidéos
✅ Administration centralisée des cours et utilisateurs

👥 Acteurs

👨‍🎓 Étudiants
Parcourir un catalogue de cours riche et multimédia
Visualiser la progression via un tableau de bord
Ajouter des cours, suivre leurs résultats

👩‍🏫 Enseignants
Créer et organiser des cours avec vidéos et quiz
Suivre l’engagement des apprenants via des statistiques
Gérer les chapitres,et les supports pédagogiques

👨‍💼 Administrateurs
Gérer les utilisateurs (bloquer/débloquer)
Activer ou désactiver des cours
Générer des rapports sur l’utilisation de la plateforme

🛠️ Fonctionnalités Clés

Étudiants			                Enseignants				                 Admin
📚 Catalogue de cours		      🧠 Création de contenu			      🔐 Gestion des utilisateurs
🧮 Quiz interactifs		        📊 Statistiques           		    📈 Suivi global
🎥 Lecteur vidéo intégré	    🛠️ Gestion des chapitres		      ⚙️ Gestion des cours

🧱 Architecture Système
L'application suit une architecture client-serveur :
![image](https://github.com/user-attachments/assets/98664b96-e893-405b-ac80-dabcec192b1a)

📚 Schémas de Données
Utilisateur (commun) : id, nom, email, mot de passe, rôle (étudiant / enseignant / admin)
Cours : id, titre, description, prix, liste de chapitres, support (vidéos, pdf,image)
Progression Étudiant : cours_id, utilisateur_id, pourcentage
Quiz : id, cours_id, questions, réponses, score

💻 Stack Technologique
Frontend (🎨)
React : composants réactifs et SPA performante
Tailwind CSS : design rapide et responsive
React Router : navigation fluide
Axios : communication avec l'API

Backend (⚙️)
Spring Boot : APIs REST sécurisées et performantes
Spring Data JPA : accès à la base de données
Maven : gestion des dépendances

Base de Données (🛢️)
MySQL : stockage relationnel des utilisateurs, cours et progression
Relations claires entre étudiants, enseignants et cours

Autres
GitHub : versioning collaboratif





