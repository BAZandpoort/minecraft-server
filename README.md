# Minecraft Server Template
This repo provides a pre-configured (optimized) template for setting up and managing a Minecraft server. This repository is designed to simplify the process of creating a customized Minecraft server, allowing users to quickly deploy their own gaming environment.

---

## Usage
### Windows
1. Install Amazon's Java version 'Corretto 17' from the official Amazon site: [Amazon Corretto](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/downloads-list.html)
2. Download and install Git from: [git-scm.cm](https://git-scm.com/)
3. (Optional but recommended) Download Visual Studio Code from: [code.visualstudio.com](https://code.visualstudio.com/Download).
4.  Open Git Bash and clone this repository with the following command: `git clone https://github.com/BAZandpoort/minecraft-server`
5. Open a terminal of choice and run the run.bat file by typing `./run.bat` in the cloned folder.
6. When you are in minecraft, enter the PUBLIC ip of the computer where you are hosting the server on. (or localhost if you are hosting and playing on the same computer)
7. Enjoy playing minecraft on your self hosted server

### Linux
1. First update and upgrade your Linux packages with: `sudo apt update && sudo apt upgrade -y`
2. Install Amazon's Java version 'Corretto 17': `wget https://corretto.aws/downloads/latest/amazon-corretto-17-x64-linux-jdk.deb`
3. install the .deb file with `sudo dpkg --install https://corretto.aws/downloads/latest/amazon-corretto-17-x64-linux-jdk.deb` (within the same directory of the file)
4. Install git with the following command: "sudo apt install git"
5. Clone this repository into a new directory with the following command: `git clone https://github.com/BAZandpoort/minecraft-server`
6. Finally run the run.sh file with `bash ./run.sh`
7. When you are in minecraft, enter the PUBLIC ip of the computer where you are hosting the server on. (or localhost if you are hosting and playing on the same computer)
8. Enjoy playing minecraft on your self hosted server

---

## Contributors
- [Cédric](https://github.com/CedricVerlinden) - for server optimization
- [Jasper](https://github.com/J4spr) - for making it work on Linux

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.