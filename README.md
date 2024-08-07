# Activities to remember
1. Configure github action secrets

2. Validate github actions workflow

3. Test the github actions CI CD flow

## 1. Configure github action secrets

```
-- actions.yaml file
  a) secrets.GKE_PROJECT > create action secret

  b) github repo > settings > security > secrets and variables > actions > repository secrets > add repository secret > 
  GKE_PROJECT
  <google cloud project id>

  c) add google service account key GKE_SA_KEY:
  goto cloud.google.com > search for service acct > select it > goto manage keys drop down list > add key > create new key > json create and download > open the json file and copy the content > create new repo secret
  GKE_SA_KEY
  <paste the copied json values>

  d) add open ai secret key OPENAI_API:
  add new repo key
  OPENAI_API
  <paste the open ai secret>

```

## 2. Validate github actions workflow
```

```
