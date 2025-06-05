<p align="center">
  <video  src="https://telegra.ph/file/62bfd3c4ce30b771a2bd3.jpg">
</p>

<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/BtwDevX/BtwMusic"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-pink?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>



1. **Upgrade & Update:**
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```

2. **Install Required Packages:**
   ```bash
   sudo apt-get install python3-pip ffmpeg -y
   ```
3. **Setting up PIP**
   ```bash
   sudo pip3 install -U pip
   ```
4. **Installing Node**
   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash && source ~/.bashrc && nvm install v18
   ```
5. **Clone the Repository**
   ```bash
   git clone https://github.com/afkXuD/afkXalexa && cd afkXalexa
   ```
6. **Install Requirements**
   ```bash
   pip3 install -U -r requirements.txt
   ```
7. **Editing Vars:**
   ```bash
   vi .env
   ```
   - Edit .env with your values.
   - Press `I` button on keyboard to start editing.
   - Press `Ctrl + C`  once you are done with editing vars and type `:wq` to save .env or `:qa` to exit editing.
8. **Installing tmux**
    ```bash
    sudo apt install tmux -y && tmux
    ```
9. **Run the Bot**
    ```bash
    bash start
    ```
