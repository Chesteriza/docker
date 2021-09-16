FROM amazon/aws-glue-libs:glue_libs_1.0.0_image_01

COPY requirements.txt ./

RUN pip install --upgrade pip && \
    pip install -r requirements.txt

EXPOSE 8888
EXPOSE 4040

# docker run -itd -p 8888:8888 -p 4040:4040 -v C:\Users\cftfda04\.aws --name glue_jupyter amazon/aws-glue-libs:glue_libs_1.0.0_image_01 /home/jupyter/jupyter_start.sh
