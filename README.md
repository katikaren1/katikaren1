### Hi there 👋

<!--
**katikaren1/katikaren1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
sudo apt update && sudo apt upgrade -y

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y

source $HOME/.cargo/env

apt install ufw -y 
ufw allow ssh 
ufw allow https 
ufw allow http 
ufw allow 4133
ufw allow 3033
ufw enable
