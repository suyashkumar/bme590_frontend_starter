# bme590_frontend_starter
This is the optional frontend starter repository for [BME590 Medical Software Design](https://github.com/mlp6/Medical-Software-Design) [final projects](https://github.com/mlp6/Medical-Software-Design/blob/master/Assignments/final_project_fall_17/final_project_f17.pdf) for Fall 2017. The code here was written during the in-class session on React (#2). The associated backend repository for melanoma classification can be found [here](https://github.com/suyashkumar/bme590_melanoma_detection).

## Deployment 
A docker compose configuration is provided to build and deploy your react application. If you need to add this configuration to your repository, simply copy the `Dockerfile` and `docker-compose.yml` into the root of your repository. To deploy this on your VM (which has docker installed):
* Clone your repository
* run `docker-compose up --build` from the root of your repository
* You should be able to visit `<vm-address-here>` in your browser and see your frontend being served. The docker compose configuration is set to serve your web frontend on port 80, which is the default port browsers issue GET requests to when you visit `adpl.suyash.io` for example. 

