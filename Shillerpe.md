# Le Ratio Shiller PE : Comprendre et Utiliser

---

## Qu'est-ce que le Shiller PE ?
- Également appelé **CAPE Ratio** (*Cyclically Adjusted Price-to-Earnings*).  
- Développé par **Robert Shiller**, prix Nobel d'économie.  
Formule :  
```math
\text{Shiller} PE = \frac{\text{Prix de l'action}}{\text{Moyenne des bénéfices ajustés sur 10 ans}}
```
- Permet de lisser les fluctuations économiques et les pics.

---

## Pourquoi est-ce utile ?
- **Évaluation des marchés :** Identifier les bulles ou sous-évaluations.
- **Approche à long terme :** Moins volatile que le PE standard.
- **Indicateur historique :** Liens avec la performance future des marchés.

---

## Comment interpréter le Shiller PE ?
- **Valeurs élevées :** Marché surévalué (ex. : avant la bulle Internet).
- **Valeurs faibles :** Opportunités d'achat.
- Moyenne historique (S&P 500) : ~16-17.
- Exemple :
  - Crise de 1929 : Shiller PE élevé.
  - Crise de 2008 : Shiller PE en baisse.

---

## Limites du Shiller PE
1. **Contexte actuel :** Peut ne pas refléter les taux d'intérêt bas.
2. **Secteurs spécifiques :** Non adapté pour analyser certaines industries.
3. **Prédiction difficile :** Pas infaillible pour prévoir les krachs.

---

## En résumé
- **Outil puissant** pour les investisseurs à long terme.
- Identifier les opportunités **d'achat** ou **de vente** sur le marché.
- Doit être utilisé avec d'autres indicateurs pour une analyse complète.

---

### Ressources
- [Site officiel de Robert Shiller](http://www.econ.yale.edu/~shiller/)
- [Données historiques du Shiller PE](https://www.multpl.com/shiller-pe)

---
```mermaid
%%{init: {
  "theme": "base",
  "themeVariables": {
    "fontFamily": "Inter, Segoe UI, Roboto, sans-serif",
    "primaryColor": "#ffffff",
    "textColor": "#1E1E1E"
  },
  "config": {
    "treemap": {
      "showValues": true,
      "padding": 14,
      "diagramPadding": 8,
      "labelFontSize": 14,
      "valueFontSize": 12
    }
  }
}}%%
treemap-beta
"PE_Ratios"
  "Ameriques":::ameriques
    "Etats-Unis": 32.87:::ameriques
    "Canada": 22.89:::ameriques
  "Europe":::europe
    "Allemagne": 24.32:::europe
    "Royaume-Uni": 18.59:::europe
    "Italie": 19.71:::europe
    "Espagne": 19.92:::europe
  "Asie":::asie
    "Japon": 24.99:::asie
    "Chine": 15.41:::asie
    "Hong Kong": 10.25:::asie
    "Coree du Sud": 15.76:::asie
    "Inde": 35.76:::asie
  "Oceanie":::oceanie
    "Australie": 21.16:::oceanie

%% 🎨 Palettes régionales (pastel premium)
classDef ameriques fill:#FFD6C9,stroke:#FF8B6A,stroke-width:1px,color:#2E2E2E;   %% corail pastel
classDef europe fill:#CBE7FF,stroke:#7AC4FF,stroke-width:1px,color:#1A1A1A;     %% bleu céleste
classDef asie fill:#D3F2D1,stroke:#79D57F,stroke-width:1px,color:#1A1A1A;       %% vert jade
classDef oceanie fill:#E7D6FA,stroke:#B98DF2,stroke-width:1px,color:#2E2E2E;    %% lavande

```
