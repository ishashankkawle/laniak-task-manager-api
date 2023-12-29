# Mule-Task-Manager-API

## Pimary Config in Anypoint Platform
- **Platform** : Cloudhub
- **Runtime Version** : 4.4.0
- **vCores** : 0.2
- **workers** : 1

## Steps to deploy api in Anypoint Platform
- Import RAML in design center and publish
- Create API instance in API manager with and add CORS policy
- Note Platform client_id and Secret in API Manager 
- Update API Autodiscovery in API
- Add below properties
    ```
    anypoint.platform.client_id=<platform env client Id>
    anypoint.platform.client_secret=<platform env client secret>
    ```
- Upload jar and deploy
