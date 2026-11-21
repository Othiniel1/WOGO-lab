# WOGO <span>•</span>

**FR** · [English below](#english)

Espace communautaire de **WOGO •**, le séquestre bilatéral du commerce en ligne informel
en zone UEMOA : l'argent de l'acheteur est retenu jusqu'à la confirmation de réception,
puis libéré au vendeur — ou maintenu en séquestre et arbitré par WOGO en cas de litige.

> **Statut : prototype d'interface.** Aucun service réel, aucun paiement, aucune donnée
> client. Les écrans sont une démonstration mobile de 390 × 844 px.

## Ce dépôt est public — et volontairement limité

| | `WOGO-Origin` (privé) | `WOGO-lab` (ce dépôt, public) |
| --- | --- | --- |
| Rôle | Trace d'antériorité, code source, prototype complet | Vitrine communautaire : idées, UI/UX, parcours, sécurité |
| Contenu | HTML, CSS, JavaScript, moteur de séquestre simulé, documentation interne | Documentation bilingue, modèles d'issues, discussions publiques |
| Accès | Équipe et personnes autorisées uniquement | Tout le monde |
| Code source | Complet | **Aucun code source de `WOGO-Origin`** |

Le code du prototype n'est pas publié ici : ce dépôt sert à recueillir des retours
exploitables sans exposer l'implémentation. Aucun extrait de code, capture d'écran
interne ou document confidentiel de `WOGO-Origin` ne doit être reproduit dans une issue.

## Ce que vous pouvez faire ici

- Proposer une amélioration d'interface ou de parcours (formulaire **Retour UI/UX**).
- Proposer une idée produit ou un axe d'amélioration (formulaire **Idée / amélioration**).
- Signaler un problème de sécurité **en privé** — jamais en issue publique (voir
  [SECURITY.md](SECURITY.md)).

Les échanges se font en **français ou en anglais**, au choix.

## Axes d'amélioration ouverts

**UI/UX** — lisibilité des montants et des frais, hiérarchie des écrans de séquestre,
contraste et tailles tactiles, états vides et erreurs, cohérence FR/EN.

**Parcours** — compréhension du lien client en trois étapes (paiement sécurisé → paiement
validé → confirmation de réception), clarté du geste de confirmation, gestion des cas
limites (lien expiré, colis partiel, acheteur injoignable), accessibilité des feuilles
glissantes au clavier.

**Sécurité** — modèles de menace du séquestre, preuve de réception, prévention de la
collusion acheteur/vendeur, conservation des preuves de litige, protection des données
personnelles, canal de signalement responsable.

## Droits

La documentation de ce dépôt est publiée pour être lue et commentée.
**Aucune licence open source n'est accordée** : le nom WOGO, la marque, les textes, la
palette et le code du prototype restent la propriété de WOGO (voir [LICENSE](LICENSE)).
Les idées et retours soumis via les issues peuvent être réutilisés par WOGO pour faire
évoluer le produit, sans contrepartie ni obligation de mise en œuvre.

## Fichiers du dépôt

```
README.md                  cette présentation (FR / EN)
CONTRIBUTING.md            comment proposer une idée ou un retour structuré
SECURITY.md                signalement responsable, règle de confidentialité
LICENSE                    droits et conditions d'utilisation
.github/ISSUE_TEMPLATE/    formulaires bilingues (UI/UX, idées) et liens utiles
```

---

## English

Community space for **WOGO •**, bilateral escrow for informal online commerce in the
UEMOA region: the buyer's money is held until delivery is confirmed, then released to the
seller — or kept in escrow and arbitrated by WOGO if there is a dispute.

> **Status: interface prototype.** No live service, no payments, no customer data.
> The screens are a 390 × 844 px mobile demonstration.

### This repository is public — and deliberately limited

| | `WOGO-Origin` (private) | `WOGO-lab` (this repo, public) |
| --- | --- | --- |
| Purpose | Proof of prior art, source code, full prototype | Community showcase: ideas, UI/UX, flows, security |
| Contents | HTML, CSS, JavaScript, simulated escrow engine, internal docs | Bilingual docs, issue templates, public discussion |
| Access | Team and authorised people only | Everyone |
| Source code | Complete | **No `WOGO-Origin` source code** |

The prototype code is not published here: this repository exists to collect actionable
feedback without exposing the implementation. No code excerpts, internal screenshots or
confidential `WOGO-Origin` documents should be reproduced in an issue.

### What you can do here

- Suggest an interface or flow improvement (the **UI/UX feedback** form).
- Propose a product idea or improvement area (the **Idea / improvement** form).
- Report a security issue **privately** — never as a public issue (see
  [SECURITY.md](SECURITY.md)).

Discussion happens in **French or English**, as you prefer.

### Open improvement areas

**UI/UX** — readability of amounts and fees, hierarchy of the escrow screens, contrast
and touch target sizes, empty and error states, FR/EN consistency.

**Flows** — clarity of the three-step customer link (secure payment → payment confirmed →
delivery confirmation), clarity of the confirmation gesture, edge cases (expired link,
partial delivery, unreachable buyer), keyboard accessibility of the sliding sheets.

**Security** — escrow threat models, proof of delivery, prevention of buyer/seller
collusion, retention of dispute evidence, personal data protection, responsible
disclosure channel.

### Rights

The documentation in this repository is published for reading and commenting.
**No open-source licence is granted**: the WOGO name, brand, texts, palette and prototype
code remain the property of WOGO (see [LICENSE](LICENSE)). Ideas and feedback submitted
through issues may be reused by WOGO to evolve the product, with no compensation and no
obligation to implement them.
