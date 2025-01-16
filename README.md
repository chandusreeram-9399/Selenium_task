# python-selenium-browserstack
Run python tests on browserstack using the SDK.

## Prerequisite
```
python3 should be installed
```

## Setup
* Clone the repo
```
git clone https://github.com/chandusreeram-9399/Bstack_assignment.git
``` 
* Install packages through requirements.txt
```
pip3 install -r requirements.txt
```
* Virtual environment(Recommended)
```
python -m venv env

```
env\Scripts\activate 

```
                       
## Set BrowserStack Credentials
* Add your BrowserStack username and access key in the `browserstack.yml` config fle.
* You can also export them as environment variables, `BROWSERSTACK_USERNAME` and `BROWSERSTACK_ACCESS_KEY`:

  #### For Linux/MacOS
    ```
    export BROWSERSTACK_USERNAME=<browserstack-username>
    export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
    ```
  #### For Windows
    ```
    setx BROWSERSTACK_USERNAME=<browserstack-username>
    setx BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
    ```

## Running tests

* Run sample test:
  - To run the sample test across platforms defined in the `browserstack.yml` file, run:
    ```
    browserstack-sdk ./tests/test.py
    ``` 
    -To run the script on your local machine or any editor 
      ./tests/localmachine.py
* 
