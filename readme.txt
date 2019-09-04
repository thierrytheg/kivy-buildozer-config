sudo apt update                 #ONLY IF NECESSARY
sudo apt install python3-pip    #ONLY IF NECESSARY


Install Cython
pip3 install cython

Install kivy

sudo add-apt-repository ppa:kivy-team/kivy
sudo apt-get update
sudo apt-get install python3-kivy

Install Kivy dependencies
sudo apt-get install -y \
    python3-pip \
    build-essential \
    git \
    python3 \
    python3-dev \
    ffmpeg \
    libsdl2-dev \
    libsdl2-image-dev \
    libsdl2-mixer-dev \
    libsdl2-ttf-dev \
    libportmidi-dev \
    libswscale-dev \
    libavformat-dev \
    libavcodec-dev \
    zlib1g-dev
    
sudo apt-get install -y \
    libgstreamer1.0 \
    gstreamer1.0-plugins-base \
    gstreamer1.0-plugins-good
    
Clone buildozer 

git clone https://github.com/kivy/buildozer.git
cd buildozer
sudo python3 setup.py install

install additional dependencies
sudo apt-get install build-essential libltdl-dev libffi-dev openjdk-8-jdk zip unzip
