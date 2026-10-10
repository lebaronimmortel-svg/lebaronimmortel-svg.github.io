# 📑 Guide de Mise en Page Avancée en Markdown

Ce document illustre comment enrichir un document Markdown avec des **sections structurées**, des **encadrés variés** et des **variations typographiques**.

---

## 1. 🔤 Typographie et Polices d'Écriture

En Markdown natif, les styles de texte se limitent au gras, à l'italique et à la police à chasse fixe (monospace). Pour aller plus loin et changer les polices, on combine le Markdown avec des balises HTML/CSS standard.

### Styles Markdown Natifs
* **Texte normal** : Police par défaut de votre lecteur Markdown.
* *Texte en italique* et **Texte en gras**.
* `Police monospace standard` : idéale pour les identifiants, raccourcis et code court.

### Personnalisation via HTML / CSS

<p style="font-family: 'Helvetica Neue', Arial, sans-serif; font-size: 1.05rem;">
  <strong>Police Sans-Serif (Moderne & Épurée) :</strong><br>
  Idéale pour les présentations contemporaines, les résumés rapides et les interfaces utilisateur claires.
</p>

<p style="font-family: 'Georgia', 'Merriweather', serif; font-size: 1.1rem; line-height: 1.6;">
  <strong>Police Serif (Élégante & Éditoriale) :</strong><br>
  Idéale pour les longs articles, les publications académiques ou les introductions littéraires nécessitant un confort de lecture prolongé.
</p>

<p style="font-family: 'Courier New', 'Fira Code', monospace; background-color: #f4f4f4; padding: 8px; border-radius: 4px;">
  <strong>Police Monospace personnalisée :</strong><br>
  Format terminal / console : SHA-256: e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
</p>

<p style="font-family: 'Brush Script MT', 'Dancing Script', cursive; font-size: 1.4rem; color: #5a3e85;">
  Police Manuscrite / Cursive : parfaite pour une note personnelle ou une citation stylisée !
</p>

---

## 2. 📦 Boîtes et Encadrés

### A. Encadrés Natifs Markdown (Blockquotes & Callouts GitHub)

Les citations simples (`>`) sont souvent rendues comme des encadrés élégants avec une bordure latérale :

> 💡 **Remarque standard** : Ceci est un encadré simple créé avec la syntaxe native Markdown `>`.

Si votre visualiseur supporte le Markdown GitHub (GFM), vous pouvez utiliser les alertes natives :

> [!NOTE]
> Informations utiles à retenir lors de la configuration du document.

> [!WARNING]
> Attention : l'interprétation du code HTML dépend de votre lecteur Markdown (Notion, Obsidian, GitHub, Pandoc, etc.).

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
```