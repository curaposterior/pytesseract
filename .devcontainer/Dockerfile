FROM opensuse/tumbleweed:latest

RUN zypper addrepo https://download.opensuse.org/repositories/home:Alexander_Pozdnyakov:tesseract5/15.4/home:Alexander_Pozdnyakov:tesseract5.repo \
 && zypper --non-interactive --gpg-auto-import-keys refresh \
 && zypper --non-interactive install tesseract gcc gcc-c++ make python3 python3-pip python3-devel

RUN zypper --non-interactive install vim git curl awk

WORKDIR /workspaces
