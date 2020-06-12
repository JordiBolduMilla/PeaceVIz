# Repositori codi font de visualització en Tableau

En aquest repositori hi trobareu el codi i els fitxers utiltzats com a fonts de  dades que s'han utilitzat per a l'elaboració d'aquesta [visualització](https://public.tableau.com/views/PeaceAgreementsUOC2020_public/story_main2?:display_count=y&:origin=viz_share_link), feta amb l'eïna Tableau, sobre l'evolució dels acords de pau al món en el període 1990 - 2019 

A continuació es llista la ubicació dels diferents arxius i documents, endreçats per carpetes, acompanyats d'una breu descripció:

Carpeta **data/**

- **pax_all_agreements_data.xlsx**

Fitxer en forma Excel amb les dades originals del projecte descarregat del lloc web [https://www.peaceagreements.org/](https://www.peaceagreements.org/)

- **pivot_groups_per_tractat.xlsx**

Fitxer en format Excel generat amb el Notebook de Jupyter sobre Python que trobareu a **code/Pivot_dades_originals** i que conté les diferents categories que es mencionen en cada acord de pau

- **pivot_paisos_per_tractat_def.xlsx**

Fitxer en format Excel generat amb el Notebook de Jupyter sobre Python que trobareu a **code/Pivot_dades_originals** i que conté els noms normalitzats juntament amb el seu corresponent codi ISO 3166-1 alpha-3 de 3 caràcters involucrats com a contrincants en cada acord de pau

- **UNSD — Methodology.xlsx**

Fitxer en format Excel que conté, entre d'altres, el codi ISO 3166-1 alpha-3 de 3 caràcters dels diferents paisos del món

**Carpeta code/**

- **PAC2_jboldum.ipynb**

Jupyter Notebook en llenguatge Python utilitzat per l'elaboració d'un informe amb l'anàlisi descriptiu del dataset utilitzat en el projecte i que trobareu, en aquest mateix repositori, a la carpeta **data/pax_all_agreements_data.xlsx** 
 
- **PAC2_jboldum.html**

Versió html del Jupyter Notebook anterior
 
- **Pivot_dades_originals.ipynb**

Jupyter Notebook en llenguatge Python utilitzat per la neteja i transformació del fitxers de dades original que trobareu a 
**data/pax_all_agreements_data.xlsx**  
 
- **Pivot_dades_originals.html**

Versió html del Jupyter Notebook anterior

  

 
