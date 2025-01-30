# Polars

La librairie polars se situe entre la librairie pandas et la librairie duckdb :

- Il peut encore des fichiers autres que utf-8 par rapport à duckdb, mais pandas accepte plus facilement des fichiers non encodés utf-8
- La fonction lazy() permet de passer les calculs intermédiaires, permettant de traiter sur des gros fichiers par rapport à pandas, mais duckdb peut traiter des fichiers beaucoup plus importants
- Polars a moins de succès que la librairie pandas, donc moins de documentation sur internet
- Polars a moins de fonctionnalités que sur Pandas, il ne peut pas par exemple, travailler directement sur un fichier Excel
- Tout comme duckdb, il est possible d'effectuer des traitements SQL avec polars (voir indexA004_sql)

**Cours présents dans le répertoire notebooks :** <br>

- indexA : introduction à polars
- indexB : tutos youtube de Keith Galli
