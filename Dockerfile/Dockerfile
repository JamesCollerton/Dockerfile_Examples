FROM busybox

RUN touch test_1.txt; \
    touch test_2.txt; \
    touch test_3.txt

ADD test_4.txt test_4.txt
ADD startup.sh startup.sh

EXPOSE 80

ENTRYPOINT ./startup.sh 
