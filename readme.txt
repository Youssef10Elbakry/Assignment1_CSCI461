we created load data:
to read the data and handle if there is any error

we created data preprossing : 
drop duplicates 
drop nulls
replace missing values using the mean and another time using the median
removed the outliers
we reduced data using pca

we created eda:
to give 5 insights
first is to get the mean
second is to get the correlation between two features
third is to display the count categorical variable for outcome column
fourth is to display the count categorical variable for BloodPressure column
fifth is to display the count categorical variable for Pregnancies column

we created model:
to get cluster the data using k-means and make them into 3 clusters

we created vis:
Create a histogram for the Outcome column
Create a histogram for the Glucose column

we installed all the requires libraries
we bulid the docker image using : docker build -t assignment1 .
we bulid the docker container using : docker run -it assignment1

we started the pipeline for load.py using : python3 home/doc-bd-a1/load.py home/doc-bd-a1/diabetes.csv
we started the pipeline for dpre.py using : python3 home/doc-bd-a1/dpre.py home/doc-bd-a1/diabetes.csv
we started the pipeline for eda.py using : python3 home/doc-bd-a1/eda.py home/doc-bd-a1/diabetes.csv
we started the pipeline for model.py using : python3 home/doc-bd-a1/model.py home/doc-bd-a1/diabetes.csv
we started the pipeline for vis.py using : python3 home/doc-bd-a1/vis.py home/doc-bd-a1/diabetes.csv

we ran the bash file to relocated the results from the container to our local machine in bd-a1/service-result/ using the bash script using:
first we opened the directory then used : ./final.sh

bonus:
GITHUB LINK : https://github.com/dox9x/assignment1-bd.git
DOCKERHUB LINK : https://hub.docker.com/repository/docker/salehayoub/mine/general 