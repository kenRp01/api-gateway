## 参考
https://www.youtube.com/watch?v=2AtL7qvTjOg&list=PLSVW22jAG8pDeU80nDzbUgr8qqzEMppi8&index=6&ab_channel=ProgrammingTechie

## やったこと
* What is API Gateway
* Use Spring Cloud Gateway MVC as the API Gateway

## keycloak
```bash
docker-compose up -d

ログインURL
http://localhost:8181/realms/master/protocol/openid-connect/auth?client_id=security-admin-console&redirect_uri=http%3A%2F%2Flocalhost%3A8181%2Fadmin%2Fmaster%2Fconsole%2F&state=41b9d996-dbe0-4c38-832f-08b40ef70443&response_mode=fragment&response_type=code&scope=openid&nonce=1de4b8e5-1101-4111-8847-d9a34212fc3c&code_challenge=a8WHykw798wl4-I0xYNiSzIZUQz0G2c1RcnYCdiNe-4&code_challenge_method=S256