# ansible-flueschmiede
Ansible-Rolle für die Flüschmiede-Konfiguration. Die hier definierte Ansible-Rolle definiert die Software-Basis, die auf Ubuntu-PCs (16.04) für Flüschmiede-Veranstaltungen zu Verfügung steht:
* Oracle Java 8 JDK
* Android Studio
* Eclipse, Eclipse JDT
* verschiedene Abhängigkeiten

Es werden die Ubuntu PPA  `ppa:paolorotolo/android-studio` und `ppa:webupd8team/java` verwendet.

# Example-Playbook
```
- hosts: localhost
  user: root
  roles:
  - ansible-flueschmiede
```
# Sonstiges
Weitere Informationen: https://www.anderscore.com/
