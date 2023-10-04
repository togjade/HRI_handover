# handover
Description of each file:

    * accel_pub.py -> publishes data from the Accelerometer connected to the STM32 board. For the connection details, refer to this [page](https://github.com/togjade/yerkebulan-s-adc_accel).
  
    * checkaudio.py -> to check the port of the connected device. 
  
    * collect_data.py -> collects the data during the object picking while wearing a tactile glove. The data was used for the ML/DL model training for the handover. 
  
    * collect_data2.py -> is the same as collect_data.py, but it doesn't record the data from the IMU sensing units.
  
    * real_time.py -> Real-time experiments with the participants and manipulator. 

open terminal 

    * cd Matlab/extern/engines/python
    * sudo python setup.py build --build-base=$(mktemp -d) install --user
