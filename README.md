# AEON-Dany

Instance personnelle d'AEON spécialisée pour les besoins de Dany.

## Missions principales

- Briefing stratégique quotidien : France, Europe, international, IA, économie, défense et médico-social.
- Veille locale : Troyes, Romilly-sur-Seine, Nogent-sur-Seine, Provins et département de l'Aube.
- Veille ESAT et ESSMS : réglementation, HAS, CNSA, ARS, MDPH, droits des travailleurs, bientraitance et autodétermination.
- Veille emploi, insertion, formation professionnelle, appels à projets, subventions et recrutements.
- Revue hebdomadaire orientée décisions, opportunités, risques et angles morts.
- Contrôle automatique de la qualité et réparation réactive des compétences défaillantes.

## Fichiers de spécialisation

- `aeon.yml` : compétences activées, sujets et programmations.
- `CLAUDE.md` : doctrine de travail, méthode de vérification et règles de prudence.
- `soul/SOUL.md` : identité et priorités de l'agent.
- `soul/STYLE.md` : style rédactionnel attendu.

## Horaires

Les programmations GitHub Actions utilisent UTC. Les créneaux ont été réglés pour correspondre principalement à l'heure de Paris en période estivale. Ils devront être décalés d'une heure lors du passage à l'heure d'hiver si une heure locale fixe est recherchée.

## Sécurité

Aucune clé API, aucun token Telegram et aucun secret ne doit être commité dans le dépôt. Les secrets doivent être enregistrés dans les GitHub Actions Secrets du dépôt.

## État technique

Ce dépôt constitue la couche de configuration personnelle. Pour exécuter réellement l'agent, il doit aussi contenir ou recevoir le moteur, les workflows et les compétences du dépôt AEON principal. Une simple configuration sans les fichiers du framework ne déclenche aucune automatisation.
