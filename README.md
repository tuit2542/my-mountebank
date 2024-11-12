# This is my Mountebank practice project

## For mocking api test, check response

### Instruction

1. install mountebank

    ```console
    foo@bar:~$ npm install -g mountebank
    ```

    or use docker

    ```console
    foo@bar:~$  docker pull bbyars/mountebank:2.9.1
    foo@bar:~$  docker run --rm -p 2525:2525 -p 4545:4545 -p 5555:5555 bbyars/mountebank:2.9.1 start 
    ```

2. to use this project

    ```console
    foo@bar:~$ mb --configfile imposters.ejs --allowInjection
    ```
