# Script-PowerShell-Ping


<img width="894" height="111" alt="commande" src="https://github.com/user-attachments/assets/51e1b1eb-ffef-4152-aaa0-bf1f4eee5a6b" />


**À quoi ça sert ?**


Ce script PowerShell permet de tester la connectivité réseau vers une ou plusieurs adresses IP ou noms de domaine (par exemple : 8.8.8.8, google.com).
Il utilise la commande Test-Connection (équivalent de ping) pour vérifier si les hôtes sont accessibles, et affiche :

Si l'hôte est accessible 


<img width="854" height="382" alt="accessible" src="https://github.com/user-attachments/assets/282afc14-6a18-4d72-937e-b2d3d59fb410" />


ou inaccessible


<img width="852" height="379" alt="inaccessible" src="https://github.com/user-attachments/assets/91f8205c-1eab-4e91-b633-868ce0ff6a0f" />


**Pourquoi l'utiliser ?**

- Pour vérifier rapidement la connectivité vers des serveurs, routeurs, ou sites internet.

- Pour mesurer la latence réseau sans outils externes.

- Utile en diagnostic réseau.

**Comment l’utiliser ?**

- Ouvre PowerShell.

- Lance le script.

- Regarde les messages pour voir si les adresses sont accessibles ou non, et combien de temps elles mettent à répondre.

‼️ Tu peux modifier les adresses testées dans la variable $ips au début du script ‼️
