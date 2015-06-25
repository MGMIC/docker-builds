FROM mgmic/qiime 
RUN apt-get update
RUN apt-get --force-yes -y install x11-xkb-utils xfonts-100dpi xfonts-75dpi xfonts-scalable xfonts-cyrillic xserver-xorg-core xvfb wget vim nano screen

RUN Xvfb :1 -screen 0 1024x768x16 &> xvfb.log  &
ENV DISPLAY :1.0
