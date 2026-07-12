# GitHub Actions CI/CD Beispiel

Dieses Repository demonstriert eine einfache CI/CD-Pipeline mit GitHub Actions.

## Staging

- Trigger: Push auf main
- Deployment per SSH
- Slack Startmeldung
- Slack Erfolg-/Fehlermeldung

## Production

- Trigger: Git Tags (v*)
- Deployment per SSH
- Slack Startmeldung
- Slack Erfolg-/Fehlermeldung

## Verwendete Secrets

- SSH_PRIVATE_KEY
- EC2_IP_STAGING
- EC2_IPS_PROD
- SLACK_WEBHOOK_URL (nicht funktionsfähig)

## Ende Banane!

Dennis Rapp - [E-Mail](mailto:info@dennisrapp.com)