# gcp

1. Set project
gcloud config set project <projectid>

2. Set compute region
gcloud config set compute/region us-central1

3. Set LOCATION
LOCATION=“us-central1”


4. List active account name 
gcloud auth list

5. List project id
gcloud config list project

6. Deploy containerized app to cloud run
gcloud run deploy --image gcr.io/$GOOGLE_CLOUD_PROJECT/helloworld --allow-unauthenticated --region=$LOCATION

7. List images in artifact registry
gcloud container images list

8. Delete container image from artifactory 
gcloud container images delete gcr.io/$GOOGLE_CLOUD_PROJECT/helloworld
