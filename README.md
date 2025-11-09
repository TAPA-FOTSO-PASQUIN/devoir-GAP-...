TAPA  FOTSO PASQUIN 25P940
Description du projet  
Ce projet est une bibliothèque utilisateur développée en C++ pour manipuler des concepts de géométrie du plan à l'aide de structures (struct) et de programmation modulaire. Il permet de gérer des points, des vecteurs et les opérations associées (translation, rotation, addition, interpolation, etc.).

Structures de base  
- Point2f : représente un point en 2D avec les coordonnées x et y  
- Vector2f : représente un vecteur en 2D avec les composantes x et y

Fonctions disponibles  

Manipulation des points  

- Add(a, b) : additionne deux vecteurs  
- Sub(a, b) : soustrait deux vecteurs (a - b)  
- Scale(v, scalar) : multiplie un vecteur par un scalaire  
- Dot(a, b) : calcule le produit scalaire entre deux vecteurs  
- Length(v) : calcule la norme (longueur) d’un vecteur  
- Normalize(v) : normalise un vecteur (le rend unitaire)  
- Lerp(a, b, t) : interpolation linéaire entre deux vecteurs selon le paramètre t  
- Determinant(a, b) : détermine le produit vectoriel (en 2D) de deux vecteurs

Fichiers du projet  

Fichiers d’en-tête  
- geometry/point.h : contient les déclarations des fonctions de manipulation de points  
- geometry/vector.h : contient les déclarations des fonctions de manipulation de vecteurs  
- geometry/utils.h : contient les fonctions pour convertir les structures Point2f et Vector2f en chaînes de caractères

Fichiers d’implémentation  
- geometry/point.cpp : implémentation des fonctions définies dans point.h  
- geometry/vector.cpp : implémentation des fonctions définies dans vector.h  
- main.cpp : fichier principal de test pour appeler et vérifier le bon fonctionnement de toutes les fonctions
