# Google web-app created for APT homework assignment 5

This assignment was a walk-through of the tutorial at: https://cloud.google.com/appengine/docs/standard/python3/building-app/

## Public Hosted Site
This is hosted at https://apthwk5.appspot.com/

### Deploying the App 

In order to deploy new changes, enable the environment mentioned below, and then run the command:

```bash
$ gcloud app deploy
```

## Locally Hosted Site

### Enabling the Environment

But can be launched locally by enabling the environment with the following command:

```bash
$ . /d/Projects/apt_assignment_5/env/Scripts/activate
```

### Launch the Locally Hosted Site

Then, to launch the locally hosted instance run the command:

```bash
$ python main.py
```

Then go to the url http://127.0.0.1:8080/ (or whatever the launched server above tells you to go to.)

