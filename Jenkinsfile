pipeline{   // Mot-clé qui montre que ceci est un pipeline
    agent any // Celui qui exécute le code (peut être spécifique indéfini comme any)
    stages{  // L'ensemble des étapes d'exécution
        stage{  // La première étape de notre pipeline
            steps{  // Les taches de l'étape
                bat "docker-compose up -d"  // Il va lancer la commande
            }
        }
    }
}