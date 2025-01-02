# 2-Wheeler-ADAS
Here 2 wheeler ADAS is trained and executed using jetson nano developer kit .Here we are doing the main training in an external Linux environment and only the trained model with less amount of losses is copied to the board along with labels.txt file.



# Custom-live-image-training-in-Jetson-Nano-using-Label-Image-tool
Do this process in your external Linux environment, other than jetson nano board(recommended).

#  Expand memory if required
- Jetson will have low RAM . So it is recommended to this process before starting your process.
- sudo apt-get install gparted
- sudo gparted
- expand memory and save

# Install required dependencies
- make sure python3 is installed
- install dependencies below
- sudo apt install python3-pip
- pip3 install opencv-python
- pip3 install imutils
- pip3 install matplotlib
- pip3 install torchvision
- pip3 install torch
- pip3 install boto3
- pip3 install pandas
- pip3 install urllib3
- sudo apt-get install pyqt5-dev-tools
- sudo apt-get install python3-lxml
- sudo apt install git
