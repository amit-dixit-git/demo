FROM java:8  
COPY Hello* /var/www/java/
RUN ls /var/www/java  
WORKDIR /var/www/java  
RUN javac Hello.java  
CMD ["java", "Hello"]  