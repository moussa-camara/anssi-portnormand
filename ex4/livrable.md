Exercice 4 : frise de notification et message

Scénario : lundi 7h30, le Port Community System est chiffré par un ransomware, le trafic des conteneurs est à l'arrêt, les fichiers contiennent des données personnelles.

Frise chronologique

| Quand | Qui | Quoi |
|---|---|---|
| T0 (lundi 7h30) | Agent de la supervision | Constate la demande de rançon et alerte la DSI |
| T0 + quelques minutes | DSI | Confirme l'attaque, isole les systèmes touchés, alerte la cellule sécurité |
| T0 + 1 h (ordre de grandeur) | Cellule sécurité | Pilote la crise, informe la direction, prépare la notification |
| Sans délai | Cellule sécurité (validation direction) | Notifie l'ANSSI/CERT-FR (LPM, SIIV touchés) |
| T0 + 24 h | Cellule sécurité | Alerte précoce (scénario cible NIS2) |
| T0 + 72 h | Cellule sécurité | Notification complète (NIS2, cible) et notification à la CNIL (données personnelles) |
| T0 + 1 mois | Cellule sécurité | Rapport final (NIS2, cible) |

Brouillon du message de notification (13 lignes)

text
Objet : Notification d'incident de sécurité – PortNormand (OIV, Transports)
Madame, Monsieur,
PortNormand, OIV du secteur Transports, vous notifie un incident détecté lundi à 7h30.
Nature : rançongiciel (fichiers chiffrés, rançon demandée) ; intrusion en cours d'analyse.
Systèmes touchés : Port Community System indisponible ; étendue en cours d'évaluation.
Données personnelles : salariés et clients concernés ; exfiltration en cours d'analyse.
Impact : trafic des conteneurs à l'arrêt ; autres activités en cours d'évaluation.
Mesures : attaque confirmée, systèmes isolés, cellule de crise activée, direction informée.
Contact : [Nom, fonction], cellule sécurité, [téléphone], [mail] ; astreinte assurée.
Contact de repli : [Nom, fonction, téléphone].
La CNIL est notifiée en parallèle ; des éléments complémentaires suivront.
Cordialement,
[Nom], responsable de la cellule sécurité (après validation de la direction)

