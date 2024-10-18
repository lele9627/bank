cmake_minimum_required(VERSION 3.29)
project(bank CXX)  # Utiliser CXX pour indiquer que c'est un projet C++

set(CMAKE_CXX_STANDARD 11)  # Utiliser la norme C++11

# Inclure le répertoire courant pour les fichiers d'en-tête
include_directories(.)


# Ajouter l'exécutable pour votre projet
add_executable(bank
        main.cpp  # Votre fichier principal
)
