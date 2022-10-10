# Crystal Structure Prediction

Crystal structures of ABO3 compounds are classified using Decision Tree and Random Forest classifier

Materials crystalizing in the perovskite crystal structure are common crystals that are currently employed for multiple applications, including transistors, solar cells, light-emitting devices, memories, catalysts, and superconductors. Perovskite Structures have been extensively studied in ceramic science and engineering, materials physics, and solid-state inorganic chemistry because of their compositional flexibility, distortion of the cation configuration, and mixed valence state electronic structure. This becomes a means for tuning the material’s properties An ideal perovskite has an ABX3 structure where A and B are two differently sized cations, and X is an anion (X is oxygen in this work). The A cation is surrounded by 12 oxygen ions in a dodecahedral environment, and the B cation is octahedrally coordinated by 6 oxygen ions. The ideal ABO3 belongs to the cubic space group Pm3m. Because of the flexibility of bond angles inherent in the perovskite structure there are many different types of distortions which can occur from the ideal structure. These distortions result in tetragonal, orthorhombic, and rhombohedral structures. This deviation from the ideal cubic structure is generally attributed to one of the three mechanisms: (i) displacement of the cations, (ii) distortions of the octahedra, and (iii) tilting of the octahedra. Thus, predicting the crystal structure of these Perovskite type oxides will find applications in the fields of solid state chemistry and ceramic engineering. Predicting the stability of the perovskite structure remains a long-standing challenge for the discovery of new functional materials for many applications including photovoltaics and electrocatalysts.

| Feature | Description |
|---------|-------------|
| v(A) | Valence of A |
| v(B) | Valence of B |
| (r(A)) | ionic radius of A cation |
| (r(B)) | ionic radius of B cation |
| (EN(A)) | Average electronegativity value of A cation |
| (EN(B)) | Average electronegativity value of B cation |
| l(A-O) | Bond length of A-O pair |
| l(B-O) | Bond length of B-O pair |
| ΔENR | Electronegativity difference with radius |
| tG | Goldschmidt tolerance factor |
| τ | New tolerance factor |
| Μ | Octahedral factor |

Target label: Lowest Distortion

Crystal Structure: cubic, tetragonal, orthorhombic, and rhombohedral structure


Model categorized perovskites into 6 different crystal structures with accuracy:
1. Decision Tree: 73.52%
2. Random Forest: 80.19%

