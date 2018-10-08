# Demoumgebung Ansible Playbooks

## Verzeichnisstruktur

- assets - Zusätzliche Dokumentation oder Dateien
- inventories - Ansible Inventory Dateien für die verschiedenen Umgebungen
- keep - Ein Ordner, der üblicherweise _nie_ eingecheckt wird mit Kennwörtern und Schlüsseln
- playbooks - Ordner für Ansible Playbooks
- roles - Ordner für Ansible Rollen

## Ansible Konfigurations-Datei
- [ansible.cfg](ansible.cfg)

## Diverse Runscripts im lokalen Verzeichnis
- [git_setup.sh](git_setup.sh)
- [run.sh](run.sh)

## Vault file
- [vault.yml](inventories/test/group_vars/all/vault.yml)

## Vault Kennwort Datei
- [vault-password-file](keep/vault-password-file)

