FROM registry:2

# ENV key=value
#ประกาศตัวแปร
# ARG TEST
#ใช้สำหรับรับ ARGUMENT จาก cmd 
# RUN echo 'HELLO'
#คือทำตอน build time

# ENTRYPOINT [ "/bin/sh","-c" ]
# RUN echo 'HELLO BAReiei'

# CMD ["echo HELLO BAR"]
#คือทำตอน run time
EXPOSE 5000


# ADD /path/host /path/container 
#ก้อปจาก url ภายนอกได้
# COPY /path/host /path/container

# คำสั่ง build
# docker build -t=test_registry .

#คำสั่ง run
# docker run test_registry แบบไม่ map port
# docker run  -p 8080:5000 test_registry


# วิธี push image เข้า registry
# เปลี่ยน image tag ให้เหมือนกับ registry
# docker tag <from> <to>
# ล้อคอิน docker ก่อน
# docker push woraponok/learn-docker:<tag: lastest>

# เมื่อขึ้นไปอยู่บน hub registry แล้วเราก็จะ pull image โดยใช้คำสั่ง
# FROM woraponok/learn-docker:tagname