# jupyter_server
## Open your terminal and connect to the server using SSH:
ssh username@server_address
## Change directory
cd /location
## Install jupyter
pip install jupyter
## Start the Jupyter Notebook server on the server
jupyter noteboook --no-browser --port=8866
## Open a new terminal window, create an SSH tunnel to the server
ssh -N -L 8866:localhost:8866 username@server_address
## Open a web browser on your local machine and go to
http://localhost:8866
## Copy and paste the token
