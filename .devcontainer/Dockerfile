FROM crystallinux/crystal
COPY pacman.conf /etc/.
COPY bashrc /root/.bashrc
RUN pacman -Syu --noconfirm && pacman -S --noconfirm neofetch