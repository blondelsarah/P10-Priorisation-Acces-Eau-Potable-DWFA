# P10-Priorisation-Acces-Eau-Potable-DWFA
Tableau de bord Power BI de priorisation des investissements pour l'accès à l'eau potable – Python, Pandas, modélisation de données, DAX.


<h1 align="center">💧 Priorisation des investissements pour l'accès à l'eau potable</h1>

<p align="center">
<b>Tableau de bord Power BI · Drinking Water For All</b><br>
Python · Pandas · Modélisation de données · Power BI · DAX
</p>

---

##  Contexte

L'association **Drinking Water For All** souhaite identifier les pays en difficulté d'accès à l'eau potable afin d'orienter un financement vers ceux où son intervention comptera le plus, selon ses trois domaines d'expertise : **création de services**, **modernisation** et **consulting**.

##  Ma démarche

- Préparation de **cinq sources publiques** (OMS, UNICEF, Banque mondiale)
- Correction des incohérences de noms de pays et restriction du périmètre aux **194 États membres de l'OMS**
- Construction d'un **modèle de données en étoile** autour d'une table pivot pays-année
- Réalisation d'un **tableau de bord Power BI de cinq pages**, de la vue mondiale au diagnostic d'un pays

##  Compétences mobilisées

**Python, Pandas, Préparation et contrôle qualité des données, Modélisation de données, Power BI, DAX, Data Visualisation, Data Storytelling.**

## 📊 Résultats

- **778 millions** de personnes sans accès à l'eau de base, dont près de la moitié en Afrique
- **870 366** décès liés à une eau non sécurisée
- Un tableau de bord qui compare les pays domaine par domaine et montre que **chaque domaine d'intervention fait ressortir des profils de pays différents**

##  Recommandations

- Choisir les pays cibles **selon le domaine d'intervention** plutôt qu'avec une liste unique
- Écarter les pays les plus instables politiquement
- Compléter l'analyse avec des **données de coût** pour estimer le rendement de chaque intervention

## 📁 Contenu du dépôt

- `Notebooks/` : préparation des données en Python
- `Presentation/` : support de soutenance
- `Dashboard/` : fichier Power BI (.pbix)
