

# Start or Stop an Instance

This script can be used to stop a running instance and starts an instance.


## Usage

```bash
╰─ ./instance_state.py -h
usage: instance_state.py [-h] [-p PROFILE_NAME] [-r REGION_NAME] -i INSTANCE_ID
Switch State of an Instance
optional arguments:
  -h, --help            shows a help message and exits
  -p PROFILE_NAME, --profile_name PROFILE_NAME
                        AWS Profile Name
  -r REGION_NAME, --region_name REGION_NAME
                        AWS Region Name
  -i INSTANCE_ID, --instance-id INSTANCE_ID
                        Instance Id
```