# firefly + traefik + authelia = !

Simple testing project for `remote_user_guard` setting in [firefly-iii](https://github.com/firefly-iii/firefly-iii).

## Run it

1. Install docker on your server
1. Add host entries to point to your server:
    ```
    127.0.0.1	myserver.com
    127.0.0.1	login.myserver.com
    ```
1. Clone the project, start docker services
    ```
    git clone https://github.com/danjl1100/firefly-traefik-authelia-example.git
    cd firefly-traefik-authelia-example/
    sudo docker-compose up
    ```
1. View the result at [myserver.com](https://myserver.com/), logging in as user=authelia, pass=authelia.
