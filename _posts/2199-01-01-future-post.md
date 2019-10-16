---
title: 'Deploy application on Google App Engine '
date: 2019-05-30
permalink: /posts/2199-01-01-future-post
tags:
  - Google
  - category1
  - category2
---

install Cloud SDK:

$ curl -O https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-240.0.0-linux-x86_64.tar.gz

tar zxvf [ARCHIVE_FILE] google-cloud-sdk
./google-cloud-sdk/install.sh
gcloud init



! gcloud deploy:
cd fdmg-236003
pip install virtualenv
virtualenv virtual
source virtual/bin/activate
pip install flask
pip install -t lib -r requirements.txt
gcloud app deploy

gcloud components update --version 240.0.0