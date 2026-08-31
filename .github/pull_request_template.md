## What changes, and why

<!-- The diff already says what changed; the "why" is what matters. -->

## Checks

<!-- Commands are in CONTRIBUTING.md. -->

- [ ] `hadolint` passes on `Dockerfile-multi-arch`
- [ ] `shellcheck -s sh root/etc/s6-overlay/scripts/*` passes
- [ ] The image builds and starts locally
- [ ] Bilingual documentation updated if observable behaviour changes
- [ ] `README.md` and `README-dockerhub.md` still agree on the facts

<!--
Reminders:
- CI runs the integration tests on amd64 and arm64; publishing waits on both
- no image is published from a pull request
- do not quote values in the `labels:` block — the quotes end up in the published label
- a s6-overlay version bump means updating the version, the three checksums and the
  README badge together
-->

---

## Ce qui change, et pourquoi

<!-- Le diff dit déjà quoi ; c'est le « pourquoi » qui compte. -->

## Vérifications

<!-- Les commandes sont détaillées dans CONTRIBUTING.md. -->

- [ ] `hadolint` passe sur `Dockerfile-multi-arch`
- [ ] `shellcheck -s sh root/etc/s6-overlay/scripts/*` passe
- [ ] L'image se construit et démarre localement
- [ ] Documentation bilingue mise à jour si le comportement observable change
- [ ] `README.md` et `README-dockerhub.md` restent d'accord sur les faits

<!--
Rappels :
- la CI exécute les tests d'intégration sur amd64 et arm64 ; la publication attend les deux
- aucune image n'est publiée depuis une pull request
- n'encadrez pas de guillemets les valeurs du bloc `labels:` : elles se retrouveraient
  telles quelles dans le label publié
- une montée de version de s6-overlay implique la version, les trois empreintes et le
  badge du README, ensemble
-->
