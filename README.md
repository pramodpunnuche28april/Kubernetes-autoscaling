Use below command to generate stress on utility-api pod

wrk -c 5 -t 5 -d 300s -H Connection: Close http://utility-api-service:8080/api/tress
