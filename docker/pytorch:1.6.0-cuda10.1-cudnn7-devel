FROM pytorch/pytorch:1.6.0-cuda10.1-cudnn7-devel

# Add the PostgreSQL PGP key to verify their Debian packages.
# It should be the same key as https://www.postgresql.org/media/keys/ACCC4CF8.asc
RUN apt-get update
RUN apt-get install ffmpeg libsm6 libxext6  -y
RUN conda install opencv -y
RUN conda install paddlepaddle -c paddle -y
RUN pip install "paddleocr>=2.0.6"

