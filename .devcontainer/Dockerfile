FROM crystallinux/crystal
COPY .devcontainer/pacman.conf /etc/.
COPY .devcontainer/bashrc /root/.bashrc
RUN pacman -Syu --noconfirm && pacman -S --noconfirm neofetch