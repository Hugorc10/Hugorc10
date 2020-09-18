### Hi there 👋

My name is Hugo Mafra from Brazil.

Primeiro configure a fonte do terminal que você ira utilizar. No MacOS, dentro de "Profiles" troque a fonte pela fonte "Fira Code - Retina - 14". Agora troque o tema que você irá utilizar, recomendo utilizar o tema Dracula https://draculatheme.com/terminal/.
Depois de instalar o tema, instale o 'Oh my Zsh' https://ohmyz.sh/.
Vamos instalar um tema para o 'Oh my Zsh' que é o Spaceship ZSH https://github.com/denysdovhan/spaceship-prompt.

SPACESHIP_PROMPT_ORDER=(
  user          # Username section
  dir           # Current directory section
  host          # Hostname section
  git           # Git section (git_branch + git_status)
  hg            # Mercurial section (hg_branch  + hg_status)
  exec_time     # Execution time
  line_sep      # Line break
  vi_mode       # Vi-mode indicator
  jobs          # Background jobs indicator
  exit_code     # Exit code section
  char          # Prompt character
)
SPACESHIP_USER_SHOW=always
SPACESHIP_PROMPT_ADD_NEWLINE=false
SPACESHIP_CHAR_SYMBOL="❯"
SPACESHIP_CHAR_SUFFIX=" "

CHKDSK /R
SFC /SCANNOW
DISM /ONLINE /CLEANUP-IMAGE /RESTOREHEALTH

<!--
**Hugorc10/Hugorc10** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
