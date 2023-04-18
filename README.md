# Import the config/quarkus-realm.json in keycloak

# Deploy the app
```
docker build -f src/main/docker/Dockerfile.jvm -t quay.io/mpaulgreen/security-openid-connect-web-authentication-quickstart-jvm:0.0.1 .
docker push  quay.io/mpaulgreen/security-openid-connect-web-authentication-quickstart-jvm:0.0.1
oc apply - deployment.yaml
```