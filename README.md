# presidio-fr — téléchargements

Installateurs et paquets de presidio-fr (le code source n'est pas public).

- **Application de bureau Windows** (passerelle locale + panneau FR / EN / 中文) : voir la release `desktop-v0.1.0`. Non signé pour l'instant : SmartScreen → « Informations complémentaires » → « Exécuter quand même ».
- **Application de bureau macOS** (Apple Silicon ; Intel à venir) : release `desktop-v0.1.0`, fichier `presidio-fr-0.1.0-arm64.dmg`. L'application n'est pas encore notarisée par Apple : au premier lancement, clic droit sur l'icône → « Ouvrir », puis « Ouvrir » dans la boîte de dialogue. Si macOS dit que l'application est « endommagée », une seule commande dans le Terminal lève la quarantaine : `xattr -d com.apple.quarantine /Applications/presidio-fr.app`. L'icône apparaît dans la barre de menus, pas dans le Dock.
- **Extension navigateur** (ChatGPT, Claude.ai, Le Chat) : voir la release `extension-v0.5.0`. Charger le dossier décompressé via `chrome://extensions` → Mode développeur → « Charger l'extension non empaquetée ».

Politique de confidentialité et rapport technique : https://github.com/xiao98/presidio-fr-docs
Jeu de données FR-PII-Bench : https://huggingface.co/datasets/JaqueBill/fr-pii-bench
