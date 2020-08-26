FROM archlinux/base
RUN pacman -Syu --noconfirm clang base-devel python ccache gsl libgcrypt gtk3 boost git openssh && yes | pacman -Scc && rm -fr /var/lib/pacman/sync/*
