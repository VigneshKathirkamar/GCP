- gcloud config list
- gcloud compute zones list
- gcloud config set compute/zone us-central1-c
- gcloud compute instances create "my-vm" \
  --machine-type "n1-standard-1" \
  --image-project "debian-cloud" \
  --image "debian-9-stretch-v20170918" \
  --subnet "default"
- gcloud compute instances delete my-vm
- gsutil mb -l <location> gs://<unique bucket name>
  Eg: gsutil mb -l US gs://my_unique_bucket_kvigne33

