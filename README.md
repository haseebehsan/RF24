
**See http://tmrh20.github.io/RF24 for all documentation for RF24**
# Python Wrapper

**Pre-Requisites**

- You must have python, boost and build-essentials. concern official docs [HERE](http://tmrh20.github.io/RF24)
- C++ Header for RF24, RF24Network, RF24Mesh (Guide Below)
- Cloned this repo

**Installing Headers**


- Install prerequisites if there are any (MRAA, LittleWire libraries, setup SPI device etc)
- Downloading the install.sh file from http://tmrh20.github.io/RF24Installer/RPi/install.sh and installing headers
    ```sh
    $ sudo wget http://tmrh20.github.io/RF24Installer/RPi/install.sh
    $ sudo chmod +x install.sh 
    $ sudo ./install.sh 
    ```
**Installing Wrappers**

- first clone this repo
    ```sh
    $ sudo git clone https://github.com/haseebehsan/RF24Python
    ```
- go inside RF24 python wrapper dir and install python wrapper for RF24
    ```sh
    $ cd ./RF24Python/pyRF24/pyRF24
    $ sudo python setup.py install
    ```
- Now go inside RF24Network python wrapper dir and install python wrapper for RF24Network
    ```sh
    $ cd ../pyRF24Network
    $ sudo python setup.py install
    ```
- Now go inside RF24Mesh python wrapper dir and install python wrapper for RF24Mesh
    ```sh
    $ cd ../pyRF24Mesh
    $ sudo python setup.py install
    ```

**Note: If you need RF24Mesh only you need RF24Network and Rf24 for that, so don't skip any step**
