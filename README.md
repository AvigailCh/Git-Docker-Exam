Build

docker build -t exam-image .

Run

docker run -it --name convertor -e PDF_NAME=avigail_pdf -v $PWD/images:/app/images -v $PWD/output:/app/output exam-image images
