FROM openliberty/open-liberty:full-java8-openj9-ubi

COPY src/main/liberty/config /config/
ADD target/coffee-shop.war /config/dropins

RUN configure.sh