# Putting Jenkins behind NGNIX reverce proxy

## Descriptionf of NGINX config file

## Additional thins to do on host machine

1. Create symbolic link at `sites-enabled`

    ```bash
    sudo ln -s /etc/nginx/sites-available/jenkins /etc/nginx/sites-enabled/
    ```

2. 