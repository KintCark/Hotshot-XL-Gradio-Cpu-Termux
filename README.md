# Hotshot-XL-Gradio-Cpu-Termux
Hey I modified the Hotshotxl gradio app.py to support cpu! It works and is faster than comfyui but I wish we could use custom sdxl models.


pkg updated && pkg upgrade -y && termux-setup-storage && pkg install wget -y && pkg install git -y && pkg install proot -y && cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh


apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y && pip install ffmpeg && apt dist-upgrade -y && apt install wget && apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y && apt-get install google-perftools &&
apt install libgoogle-perftools-dev && pip install moviepy==1.0.3 && pip install cmake accelerate 


git clone https://github.com/openai/triton.git;
cd triton;

pip install ninja cmake wheel;

pip install -e python

you will get an error ignore it and continue 

git clone https://github.com/RamboRogers/Hotshot-XL-Gradio

cd Hotshot-XL-Gradio

once you git clone hotshotxl gradio download my hotshot gradio cpu zip extract it then navigate to your hotshotxl gradio folder in ubuntu root folder
delete the requirements txt file in that folder and copy the py file and requirements.txt from the zip you extracted to the ubuntu hotshotxl gradio folder then all you got a do is next step.


pip install -r requirements.txt

python cpuhsxl_modified.py


