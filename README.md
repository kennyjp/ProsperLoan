# Analyse des données de Prêts dans une société de finance
## Par Jean-Philippe ONDO


## ProsperLoanData.csv

> Nous avons explorer un ensemble de données contenant 113 937 prêts avec 81 variables sur chaque prêt, y compris le montant du prêt, le taux de l'emprunteur (ou taux d'intérêt), le statut actuel du prêt, le revenu de l'emprunteur et bien d'autres choisi parmit la liste suivant [site](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub) fournit par Udacity. Les attributs/variables du jeu de données sont expliqués dans le tableau [dictionnaire de données](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1620931527882000&usg=AOvVaw3vbnU-g9ISX-OFBKzCIkqf)
Tout d'abord nous avons importer les différente bibliothéques ainsi que l'ensemble de données choisi. Puis son procéssus d'analyse a été structurer comme suite:
- Evaluation visuel
- Evaluation Programmatique
- Observations 
- Nettoyages sur la base de définition du problémes, code et test
- Explorations Univariés sur la base des questions visuel et observations
- Explorations Bivariés sur la base des questions visuel et observations
- Explorations Multivariés sur la base des questions visuel et observations
- Conclusions sur l'ensemble des visuels

## Résumé des conclusions

> L'ensemble de données sur les prêts Prosper a fourni une grande quantité de variables lors du téléchargement, qui ont été regroupées aux fins de cette analyse en dix-sept (17) variables.
Nous sommes allés plus loin pour effectuer des manipulations de données, y compris le nettoyage et la manipulation des données et au cours de cette manipulation, deux (2) variables supplémentaires ont été créées - _LoanOriginationMonth_ et _LoanOriginationYear_.

> Trois questions majeures ont guidé l'ensemble de l'exploration et de l'analyse de l'ensemble de données sur les prêts, à savoir :
- Quels facteurs affectent le statut de résultat d'un prêt
- Ce qui affecte le TAEG ou le taux d'intérêt de l'emprunteur
- Existe-t-il des différences entre les prêts en fonction du montant initial du prêt ?

> Sur la base de ces questions de recherche, nous avons identifié QUATRE(3) principales variables d'intérêt à savoir
_LoanStatus, BorrowerInterest_ et _LoanOriginalAmount_. et quelques autres variables prédictives, à savoir : _Term, ListCategory, IncomeRange, StatedMonthlyIncome, EmploymentStatus, IsBorrowerHomeOwner, LoanOriginationQuarter, LoanOriginationMonth_ et _LoanOriginationYear_, etc.

> Nous avons ensuite procédé à une analyse exploratoire avec des visualisations univariées, des visualisations bivariées et des visualisations multivariées de toutes les variables principales et prédictives pour recueillir des informations sur les questions de recherche.Les idées suivantes ont constitué la base des réponses à nos questions de recherche à partir des parcelles d'exploration et des analyses effectuées.Il est donc à noter que les montants de prêt plus élevés sont plus susceptibles d'avoir un statut de prêt ***En défaut*** ou ***En souffrance***, tandis que les montants de prêt inférieurs ont un taux plus élevé d'achèvement.



## Informations clés pour la présentation

> Sélectionnez un ou deux fils principaux de votre exploration pour peaufiner votre présentation. Notez ici tout changement de conception à partir de votre étape d'exploration.