# gcp

1. Set project
<br/>gcloud config set project <projectid>

2. Set compute region
<br/>gcloud config set compute/region us-central1

3. Set LOCATION
<br/>LOCATION=“us-central1”


4. List active account name 
<br/>gcloud auth list

5. List project id
<br/>gcloud config list project

6. Deploy containerized app to cloud run
<br/>gcloud run deploy --image gcr.io/$GOOGLE_CLOUD_PROJECT/helloworld --allow-unauthenticated --region=$LOCATION

7. List images in artifact registry
<br/>gcloud container images list

8. Delete container image from artifactory 
<br/>gcloud container images delete gcr.io/$GOOGLE_CLOUD_PROJECT/helloworld
