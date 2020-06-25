FROM python:latest

RUN pip install numpy
RUN pip install paramiko
RUN pip install imutils
RUN pip install opencv-python
ADD start.sh /
ADD yolo.py /
ADD processing_script.py /
ADD /processed_split_images /processed_split_images
ADD /split_images /split_images
ADD /yolo-coco /yolo-coco

ENTRYPOINT ["./start.sh"] 

