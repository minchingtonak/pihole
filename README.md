## Installation

1. Use `rpi-imager` to flash image onto SD card
2. After booting OS, SSH into the pi
3. `sudo apt update && sudo apt upgrade`
4. `curl -sSL https://get.docker.com | sh`
5. `sudo usermod -aG docker $USER`
6. log out and back in
7. `git clone https://github.com/minchingtonak/pihole.git && cd pihole`
8. add a `.env` file and populate values for the required variables
9. `docker compose up -d`
10. `docker compose logs -f` to tail logs
