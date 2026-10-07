# Cheat Sheet Markdown pour VS Code

Voici le guide de survie de la syntaxe Markdown, optimisé pour **Visual Studio Code** avec les raccourcis clavier natifs par défaut.

---

## 1. Raccourcis Clavier VS Code (Indispensables)

| Action | Raccourcis (Windows/Linux) | Raccourcis (macOS) |
| :--- | :--- | :--- |
| **Ouvrir l'aperçu (Preview)** | `Ctrl` + `Shift` + `V` | `Cmd` + `Shift` + `V` |
| **Ouvrir l'aperçu à côté** | `Ctrl` + `K` puis `V` | `Cmd` + `K` puis `V` |
| **Mettre en Gras** | `Ctrl` + `B` | `Cmd` + `B` |
| **Mettre en Italique** | `Ctrl` + `I` | `Cmd` + `I` |

---

## 2. Structure et Titres

Ajoutez un ou plusieurs `#` suivis d'un espace en début de ligne.

```markdown
# Titre 1 (Titre principal du document)
## Titre 2 (Sections principales)
### Titre 3 (Sous-sections)
#### Titre 4
##### Titre 5
###### Titre 6
```

---

## 3. Formatage du Texte

| Style | Syntaxe Markdown | Rendu attendu |
| :--- | :--- | :--- |
| **Gras** | `**Texte**` ou `__Texte__` | **Texte** |
| *Italique* | `*Texte*` ou `_Texte_` | *Texte* |
| ***Gras & Italique*** | `***Texte***` | ***Texte*** |
| ~~Barré~~ | `~~Texte~~` | ~~Texte~~ |

---

## 4. Listes et Listes de Tâches

### Listes à puces (Non ordonnées)
Utilisez `-`, `*`, ou `+` suivi d'un espace.
```markdown
- Élément A
- Élément B
    - Sous-élément B1 (Faire une tabulation)
```

### Listes numérotées (Ordonnées)
```markdown
1. Premier élément
2. Deuxième élément
```

### Listes de tâches (To-Do)
```markdown
- [ ] Tâche à faire
- [x] Tâche terminée
```

---

## 5. Liens et Images

* **Lien hypertexte** : `[Texte du lien](https://example.com)`
* **Image** : `![Texte alternatif](chemin/vers/image.png)`

---

## 6. Blocs de Code (Coloration VS Code)

VS Code excelle dans la coloration syntaxique du code. Utilisez les trois accents graves (\`\`\`) suivis de l'identifiant du langage.

```markdown
```python
def saluer():
    print("Bonjour depuis VS Code !")
```
```

---

## 7. Citations et Lignes de Séparation

* **Citation block** : `> Ceci est une citation.`
* **Séparateur horizontal** : Remplissez une ligne avec trois tirets ou plus : `---`

---

## 8. Tableaux

Séparez les colonnes par des barres verticales `|` et utilisez des tirets `-` sous la ligne d'en-tête.

```markdown
| Article | Quantité | Prix |
| :--- | :---: | ---: |
| Ordinateur | 1 | 899 € |
| Souris | 2 | 25 € |

(Astuce alignement : `:---` à gauche, `:---:` au centre, `---:` à droite)
```

---
*Généré automatiquement pour votre usage sur VS Code.*
