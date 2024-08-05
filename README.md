# CBSD Client for OpenSAS

1. Make sure that the Certs are generated in OpenSAS with this machine's IP (accesscible from other VMs) and placed in the Certs folder here. Also, the proper gnb yml  file is copied from your srsRAN/configs folder. modify the run.py script to include any specific srsRAN config file. Make appropriate changes in the run.py and CBSD.py.


2. Modify run.py to add you gnb yml file name:
![image](https://github.com/user-attachments/assets/734da49e-360f-4a26-b8f8-3c442607c84e)

3. Modify CBSD.py to inculde OpenSAS IP and proper CBSD client certificate path:
   ![image](https://github.com/user-attachments/assets/121ad011-faba-4fb6-940e-7f5ba29461c6)
