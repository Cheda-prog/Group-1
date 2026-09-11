# Software Testing Lab
This repo contains starter code for test coverage exercises. Follow the instructions on the [class website](https://johnxu21.github.io/teaching/CS472/Timetable/dynamic_analysis/?) to get started.

## Additional Information

### Python Version(s)
You need Python `>= 3.9`. The exercise has been tested on `3.9.6` and `3.13.5`, and any Python `3.9+` should work without configuration changes. Python 3.8 is end-of-life and is no longer supported by the pinned dependencies. **If you are facing any configuration issue, please reach out to the T.A**. 

### Upgrading PIP:
Sometimes it is useful to upgrade `pip` before installing dependencies. If you like, run: `pip install --upgrade pip` and later install the dependencies using: `pip install -r requirements.txt`

### Python Virtual Environment - Optional
 - It is a good practice to configure python virtual environment. Use the commands below to setup python virtual environment on `Linux/MacOS` or `Windows OS`
   ```
   # For Linux/MacOS

   python3 -m venv venv
   source venv/bin/activate
   ```
   **NB:** Replace `python3` with any of the versions listed above e.g: `python3.11` or `python3.13`. 

   - For `Window OS` user, the easest approach is to install `virtualenv` by running `pip install virtualenv`. The next step is pretty much similar to above;
   ```
   # For Window OS

   python3 -m virtualenv venv
   venv\Scripts\activate
   ```
   - Install required dependencies using `pip3 install -r requirements.txt`
