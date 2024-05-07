#To coppy the repo:
git clone https://github.com/JPLapointe1971/Code11_jplapointe.git

#to build the Docker image:
cd Code11_jplapointe
docker build -t sample:dev .

#to start the container:
docker run -dp 3001:3000 --name jplaointeCode11 sample:dev
