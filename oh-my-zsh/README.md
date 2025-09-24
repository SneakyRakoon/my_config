# Oh My Zsh Configuration

## Description
Configuration personnalisée pour Oh My Zsh, un framework pour le shell Zsh qui améliore l'expérience en ligne de commande.

## Installation
1. Assurez-vous d'avoir Zsh installé
2. Installez Oh My Zsh : `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
3. Copiez les fichiers de configuration dans votre répertoire home

## Fonctionnalités
- Thème personnalisé
- Plugins utiles pour le développement
- Alias pratiques
- Configuration optimisée pour la productivité

## Usage
Redémarrez votre terminal ou exécutez `source ~/.zshrc` pour appliquer la configuration.

## Repositories à cloner

### Dracula Theme
```bash
git clone https://github.com/dracula/zsh.git ~/.oh-my-zsh/custom/themes/dracula
ln -s ~/.oh-my-zsh/custom/themes/dracula/dracula.zsh-theme ~/.oh-my-zsh/custom/themes/dracula.zsh-theme
```

### Zsh Autosuggestions
```bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

Ajoutez `zsh-autosuggestions` à votre liste de plugins dans `~/.zshrc` :
```bash
plugins=(git zsh-autosuggestions)
```