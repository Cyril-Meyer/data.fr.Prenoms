# data.fr.Prenoms

**raw data**  
Fichier des prénoms de 1900 à 2020  
Source : [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/fichier-des-prenoms-de-1900-a-2019/) → [insee.fr](https://www.insee.fr/fr/statistiques/2540004?sommaire=4767262)  
Licence : Licence Ouverte / Open Licence version 2.0

## Analyses
Pour chaque année de 1900 (inclus) à 2020 (inclus) :
1. Le nombre de fois ou le prénom a été donné (pour les prénoms les plus données, i.e. dans le top 2 d'une année).
2. Le nombre de prénoms différents.
3. La moyenne et l'écart type du nombre d'affectations par prénom.

## Avertissement biais
* Les années "XXXX" sont ignorées
* Pour les analyses 2 et 3, les "PRENOMS_RARES" sont considérés comme donnée en moyenne 20 fois.
  * e.g. en 2020, pour les hommes, il y a 26109 "PRENOMS_RARES". Dans nos analyses, nous considérons que 1305 prénoms ont été donnés 20 fois (erreur dû à la division entière).

*insee.fr*
> Conditions portant sur les prénoms retenus
> 1. Sur la période allant de 1900 à 1945, le prénom a été attribué au moins 20 fois à des personnes de sexe féminin et/ou au moins 20 fois à des personnes de sexe masculin
> 2. Sur la période allant de 1946 à 2020, le prénom a été attribué au moins 20 fois à des personnes de sexe féminin et/ou au moins 20 fois à des personnes de sexe masculin
> 3. Pour une année de naissance donnée, le prénom a été attribué au moins 3 fois à des personnes de sexe féminin ou de sexe masculin
> 
> Les effectifs des prénoms ne remplissant pas les conditions 1 et 2 sont regroupés (pour chaque sexe et chaque année de naissance) dans un enregistrement dont le champ prénom (PREUSUEL) prend la valeur «PRENOMS_RARES». Les effectifs des prénoms remplissant la condition 2 mais pas la condition 3 sont regroupés (pour chaque sexe et chaque prénom) dans un enregistrement dont le champ année de naissance (ANNAIS) prend la valeur «XXXX».


# Visualisation
## 1

<iframe src="top_prenom_1.html" width="100%" height="400" scrolling="no" style="border:none;">top_prenom_1</iframe>
[plein écran](top_prenom_1.html)


<iframe src="top_prenom_2.html" width="100%" height="400" scrolling="no" style="border:none;">top_prenom_2</iframe>
[plein écran](top_prenom_2.html)


## 2

<iframe src="nombre_prenom.html" width="100%" height="400" scrolling="no" style="border:none;">nombre_prenom</iframe>
[plein écran](nombre_prenom.html)


## 3

<iframe src="affectation_mean.html" width="100%" height="400" scrolling="no" style="border:none;">affectation_mean</iframe>
[plein écran](affectation_mean.html)


<iframe src="affectation_std.html" width="100%" height="400" scrolling="no" style="border:none;">affectation_std</iframe>
[plein écran](affectation_std.html)
