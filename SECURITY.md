# Sécurité / Security

**FR** · [English below](#english)

## Règle de confidentialité

**Ne publiez jamais une vulnérabilité sensible dans une issue, une pull request ou une
discussion.** Une faille rendue publique avant correction expose les utilisateurs, les
vendeurs et les partenaires de paiement de WOGO. Les issues publiques de ce dépôt sont
visibles immédiatement et indexées.

## Comment signaler

1. **Avis privé GitHub** — onglet **Security** de ce dépôt → **Report a vulnerability**.
   C'est le canal préféré : la discussion reste privée entre vous et les mainteneurs.
2. **Sinon**, écrivez à `security@wogo.example` *(adresse de démonstration, à remplacer
   avant la mise en service)*.

Merci d'indiquer :

- le composant concerné (prototype, parcours client, séquestre, documentation) ;
- les étapes de reproduction ;
- le résultat observé et le résultat attendu ;
- la version du navigateur et du système ;
- une preuve minimale (capture, extrait de console), **sans donnée personnelle réelle**.

N'incluez jamais de clé, de jeton ou de mot de passe dans un rapport, et n'exploitez pas la
faille au-delà du strict nécessaire à la démonstration.

## Périmètre

Ce dépôt public ne contient **que de la documentation** et des modèles d'issues. Il n'y a
ni serveur, ni base de données, ni code exécuté ici.

Sont donc dans le périmètre : une fuite d'information dans la documentation, un modèle
d'issue qui pousserait à publier des données sensibles, une usurpation du nom WOGO, un
canal de signalement défaillant.

Sont hors périmètre : l'absence d'authentification, de chiffrement ou de limitation de
débit (ce dépôt n'exécute rien), les montants et comptes fictifs du prototype, les
rapports de scanner sans scénario exploitable.

## Notre engagement

- Accusé de réception sous 3 jours ouvrés.
- Première évaluation sous 10 jours ouvrés.
- Correction ou mesure d'atténuation avant toute communication publique.
- Crédit du signalement si vous le souhaitez, une fois la correction disponible.

Nous vous demandons de ne pas accéder à des données qui ne vous appartiennent pas, de ne
pas dégrader le service, de ne pas tester sur des données réelles et de ne pas publier de
détails avant accord écrit de l'équipe.

---

## English

### Confidentiality rule

**Never publish a sensitive vulnerability in an issue, pull request or discussion.** A
flaw made public before it is fixed exposes WOGO's users, sellers and payment partners.
Public issues in this repository are visible immediately and indexed.

### How to report

1. **GitHub private advisory** — this repository's **Security** tab → **Report a
   vulnerability**. This is the preferred channel: the discussion stays private between
   you and the maintainers.
2. **Otherwise**, email `security@wogo.example` *(demonstration address, to be replaced
   before going live)*.

Please include:

- the component concerned (prototype, customer flow, escrow, documentation);
- reproduction steps;
- observed and expected results;
- browser and OS version;
- minimal evidence (screenshot, console excerpt), **with no real personal data**.

Never include keys, tokens or passwords in a report, and do not exploit the flaw beyond
what is strictly needed to demonstrate it.

### Scope

This public repository contains **documentation only** and issue templates. There is no
server, no database and no code executed here.

In scope: an information leak in the documentation, an issue template that would
encourage publishing sensitive data, impersonation of the WOGO name, a broken reporting
channel.

Out of scope: missing authentication, encryption or rate limiting (nothing runs here),
the prototype's fictional amounts and accounts, scanner reports with no exploitable
scenario.

### Our commitment

- Acknowledgement within 3 business days.
- First assessment within 10 business days.
- Fix or mitigation before any public communication.
- Credit for your report if you wish, once the fix is available.

We ask you not to access data that is not yours, not to degrade the service, not to test
on real data, and not to publish details before written agreement from the team.
