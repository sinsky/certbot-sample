# certbot sample - google domains

1. Clone repo

  Clone this repository.
  ```shell
  git clone https://github.com/sinsky/certbot-sample
  ```

2. Create credential file

  Run the following command.
  ```shell
  touch /var/lib/letsencrypt/dns_google_domains_credentials.ini
  ```

3. Write credentials

  Write your credentials as follows.
  ```ini
  dns_google_domains_access_token = ""
  ```
  
  > See https://github.com/aaomidi/certbot-dns-google-domains#credentials for details.

4. Run docker command

  Run the following command.
  ``` shell
  docker compose up
  ```
