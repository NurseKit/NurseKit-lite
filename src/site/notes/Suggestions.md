---
{"dg-publish":true,"permalink":"/Suggestions/","tags":["suggestions","feedback","contact"],"noteIcon":"","dg-note-properties":{"nom":"Suggestions & Retours","tags":["suggestions","feedback","contact"],"revision":"2026-06-19"}}
---


> [!abstract] Suggestions & Retours
> Tu as trouvé une erreur ? Une fiche manquante ? Une suggestion pour améliorer NurseKit ?
> Envoie ton message ci-dessous, toutes les suggestions sont lues et prises en compte.

<div class="suggestion-form-wrapper">

<form action="https://formspree.io/f/mnjyewro" method="POST">
  <input type="hidden" name="_subject" value="Nouvelle suggestion NurseKit" />
  <input type="hidden" name="_next" value="https://nursekit.pages.dev/merci" />
  <input type="text" name="_gotcha" style="display:none" />

  <div class="form-group">
    <label for="prenom">Prénom (optionnel)</label>
    <input type="text" id="prenom" name="prenom" placeholder="Ton prénom ou pseudo..." />
  </div>

  <div class="form-group">
    <label for="annee">Année IFSI (optionnel)</label>
    <select id="annee" name="annee">
      <option value="">-- Sélectionner --</option>
      <option value="1ere">1ère année</option>
      <option value="2eme">2ème année</option>
      <option value="3eme">3ème année</option>
      <option value="IDE diplome">IDE diplômé(e)</option>
      <option value="autre">Autre</option>
    </select>
  </div>

  <div class="form-group">
    <label for="type">Type de retour</label>
    <select id="type" name="type" required>
      <option value="">-- Sélectionner --</option>
      <option value="erreur">🔴 Erreur dans une fiche</option>
      <option value="fiche-manquante">📄 Fiche manquante</option>
      <option value="amelioration">💡 Suggestion d'amélioration</option>
      <option value="remerciement">💚 Remerciement</option>
      <option value="autre">❓ Autre</option>
    </select>
  </div>

  <div class="form-group">
    <label for="fiche">Fiche concernée (si applicable)</label>
    <input type="text" id="fiche" name="fiche" placeholder="Ex : IDM, Morphine, ECG..." />
  </div>

  <div class="form-group">
    <label for="message">Ton message <span style="color:#e74c3c">*</span></label>
    <textarea id="message" name="message" rows="5" placeholder="Décris la correction, la fiche manquante ou ta suggestion..." required></textarea>
  </div>

  <div class="form-group">
    <label for="email">Ton email (pour recevoir une réponse, optionnel)</label>
    <input type="email" id="email" name="email" placeholder="ton@email.fr" />
  </div>

  <button type="submit" class="submit-btn">Envoyer ma suggestion →</button>
</form>

</div>

<style>
.suggestion-form-wrapper {
  max-width: 600px;
  margin: 2rem auto;
}
.form-group {
  margin-bottom: 1.2rem;
  display: flex;
  flex-direction: column;
  gap: 0.4rem;
}
.form-group label {
  font-weight: 600;
  font-size: 0.9rem;
  color: var(--text-normal);
}
.form-group input,
.form-group textarea,
.form-group select {
  padding: 0.6rem 0.8rem;
  border: 1px solid var(--background-modifier-border);
  border-radius: 6px;
  background: var(--background-secondary);
  color: var(--text-normal);
  font-size: 0.95rem;
  font-family: inherit;
  transition: border-color 0.2s;
}
.form-group input:focus,
.form-group textarea:focus,
.form-group select:focus {
  outline: none;
  border-color: var(--interactive-accent);
}
.form-group textarea {
  resize: vertical;
  min-height: 120px;
}
.submit-btn {
  background: linear-gradient(135deg, #6366F1, #8B5CF6);
  color: white;
  border: none;
  padding: 0.75rem 2rem;
  border-radius: 6px;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: opacity 0.2s;
  width: 100%;
  margin-top: 0.5rem;
}
.submit-btn:hover { opacity: 0.85; }
</style>

---

> [!info] Confidentialité
> Tes données ne sont utilisées que pour répondre à ta suggestion. Aucun partage avec des tiers.
> NurseKit est un projet étudiant sans but commercial.
