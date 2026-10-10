<div style="background-color: black; color: white; padding: 16px; border-radius: 6px;">

# 📑 Guide de Mise en Page Avancée en Markdown


## 1. 🔤 Typographie et Polices d'Écriture


### Styles Markdown Natifs


### Personnalisation via HTML / CSS


## 2. 📦 Boîtes et Encadrés

### A. Encadrés Natifs Markdown (Blockquotes & Callouts GitHub)

---

### B. Encadrés Avancés Personnalisés (HTML / CSS)

Pour un contrôle total des couleurs, bordures et arrondis :

<div style="background-color: #eff6ff; border-left: 5px solid #3b82f6; padding: 15px; border-radius: 6px; margin: 15px 0;">
  <strong style="color: #1d4ed8;">ℹ️ Encadré d'Information</strong>
  <p style="margin: 8px 0 0 0; color: #1e3a8a;">
    Ce bloc utilise un fond bleu pastel et une bordure gauche pleine pour mettre en valeur une annonce importante.
  </p>
</div>

<div style="background-color: #f0fdf4; border: 1px solid #86efac; border-left: 6px solid #22c55e; padding: 15px; border-radius: 8px; margin: 15px 0;">
  <strong style="color: #15803d;">✅ Encadré de Succès</strong>
  <p style="margin: 8px 0 0 0; color: #14532d;">
    Votre document est parfaitement valide et prêt à être exporté au format PDF ou HTML.
  </p>
</div>

<div style="background-color: #fef2f2; border: 1px solid #fca5a5; padding: 15px; border-radius: 8px; margin: 15px 0;">
  <strong style="color: #b91c1c;">⚠️ Encadré Critique / Alerte</strong>
  <p style="margin: 8px 0 0 0; color: #7f1d1d;">
    Veillez à ne pas surcharger vos documents de polices exotiques si le document final est destiné à l'impression.
  </p>
</div>

---

## 3. 📊 Tableau Synthétique des Syntaxes

| Élément | Syntaxe Markdown | Rendu / Effet |
| :--- | :--- | :--- |
| **Monospace** | `` `code` `` | Police à largeur fixe |
| **Citation** | `> Texte` | Encadré avec barre verticale |
| **Police spécifique** | `<span style="font-family: ...">` | Changement de fonte via CSS |
| **Carte / Cartouche** | `<div style="border: 1px solid...">` | Bloc encadré complet |

---

## 4. 📝 Résumé Pratique

```markdown
<!-- Modèle d'encadré rapide prêt à copier-coller -->
<div style="border: 2px dashed #6366f1; background: #eef2ff; padding: 12px; border-radius: 8px; font-family: sans-serif;">
  <strong>💡 Astuce :</strong> Collez votre contenu ici !
</div>
</div>
```