FROM openjdk:8-slim-buster
WORKDIR /app
#ENV TZ Asia/Baku
COPY  ./target/*.*ar .
RUN ln -sfn *.*ar app
ENTRYPOINT ["java", "-jar", "./app"]
CMD [""]


