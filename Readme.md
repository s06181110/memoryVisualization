# 卒業研究

## スタックメモリの可視化


## Quickstart

### Requirements
- Mac OS
- Xcode
- Node.js

### Install
```bash
$ git clone https://github.com/s06181110/memoryVisualization
$ cd memoryVisualization
```
- Backend
    ```bash
    $ cd project_dir/backend;
    ```
    ### Create an environment with Python in Xcode 
    ```bash
    $ xcrun python3 -m venv venv
    ```
    ### Activate virtual environment
    ```bash
    # When you want to end "deactivate"
    $ . venv/bin/activate
    ```
    ### Get some library
    ```bash
    $ make prepare
    ```
    ### Launch
    ```bash
    $ make test
    ```

- Frontend
    ```bash
    $ cd project_dir/frontend;
    ```
    ### Get some library
    ```bash
    $ npm install
    ```
    ### Launch
    ```bash
    $ npm run serve
    ```
