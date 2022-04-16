# Python and loops

The running of this one is for the python edition so rather than the normal ./reach run we want to initiate a python virtual environment, install the needed reach dependency, run reach and then exit the virtual environment.  Below are the full commands.



```shell
([ -d ./venv ] || python3 -m venv ./venv) && source ./venv/bin/activate

pip install --upgrade reach-rpc-client


# run this for more hands
 ./reach rpc-run python3 -u ./index.py


# exit when donw

 deactivate
```
