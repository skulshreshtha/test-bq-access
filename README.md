# test-bq-access

## Steps to follow
1. Follow the gcloud CLI download and login process as described in the image `steps_for_gcloud_login`, you will have a file called `application-default-credentials.json`
saved at your `$HOME/.config/gcloud/` directory. This file contains credentials which will be used by any application / project you develop locally without
providing any other credentials.  
2. What that also means is that now you can authenticate as yourself, and since you have live DWH access the applications you run locally will have the same access.

## To test the setup
1. Clone this repo.
2. Setup a virtual environment.
3. Install the required packages using `pip install -r requirements.txt`.
4. You can test the setup works by running the notebook `testing.ipynb`.
