# Traduction française de ProcessWire

Traduction actuelle adaptée pour PW 2.3
Lors de nouvelles versions, nous allons créer de nouveaux tags permettant de retrouver les traductions pour les anciennes versions(à partir de 2.3).

### Pour les traducteurs - normes

Afin de donner une meilleure expérience à l'utilisateur, on va utiliser des normes.

###### À discuter..
- Ne pas utiliser les mots Upload/Download, mais plutôt téléversement/télécharger. - ceci est encore à discuter, upload/download est maintenant dans plusieurs dictionnaires et est reconnu. Le but est de trouver quelque chose de facile à comprendre même pour les débutants.
- L'utilisation du mot plugin est autorisée pour le moment, par exemple "un plugin de TinyMCE". - ceci est à discuter afin de voir s'il y a de meilleures alternatives.
- L'utilisation de mots très connus comme "URL" est permise, mais lorsque ceci s'adresse directement à un utilisateur peu avancé, tenter d'utiliser un mot français si possible(lien?).
- La traduction de template sera gabarit.

- Lorsque vous n'êtes pas certain du contexte: laissez-le vide ou si vous êtes à l'aise avec le code, allez voir le code afin de comprendre le contexte.
- Quand le mot est pareil en français et en anglais, laissez-le vide.


Ces normes sont modifiables, vous pouvez toujours créer une "issue" sur github afin de créer une discussion sur les changements que vous proposez. Le but est de créer la meilleure expérience possible.

Lorsqu'il y a des fautes d'orthographe, ne pas hésiter à corriger, personne n'est parfait ;).

### Pour les traducteurs - priorités

- Les champs "Module title" et "Module summary"(parfois nommés "getModuleInfo title" et "getModuleInfo summary") ne sont pas nécessaire, vous pouvez les laisser vide(c'est utilisé seulement dans la page d'installation/désinstallation des modules).
- Le fichier ProcessTemplate sera à faire en dernier vu sa taille(227 phrases) et aussi il n'est pas très utile pour l'instant vu que c'est le fichier de Configuration-->Templates. Rarement utilisé par les clients.
- Le fichier ProcessField va attendre aussi, ceci est pour Configuration-->Fields. Encore quelque chose de peu utilisé par les clients.

Pour tout le reste, c'est ce qui est notre priorité.


### Les fichiers qui sont exclus de la traduction, donc non-présent dans ce répertoire

###### Par cause d'être seulement des "module title" et "module summary":
- TextformatterEntities
- InputfieldButton
- InputfieldAsmSelect
- InputfieldFieldset
- InputfieldFloat
- InputfieldForm
- InputfieldSubmit
- ProcessHome
- ProcessRole
- ProcessPermission
- ProcessPageView
- PageRender
- SystemUpdater
