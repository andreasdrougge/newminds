# newminds
New Minds Acadamy

## Load Testing
Apache Bench <br>
sudo apt–get install –y apache2<br>
<br>
ab -kc 20 -n 1000 https://suavoo.com/ <br>
<br>
<br>
## Dot.net example
https://github.com/dotnet-presentations/aspnetcore-for-beginners <br>
<br>
## Tools:
### CURL <br>
curl -I https://suavoo.com/ <br>
curl -I --http2 https://suavoo.com/ <br>
Postman - https://www.getpostman.com/ <br>
SoapUI - https://www.soapui.org/downloads/soapui.html <br>
GraphiQL - https://github.com/graphql/graphiql <br>
 <br>
### REST
https://jsonplaceholder.typicode.com <br>
https://httpbin.org <br>
 <br>
### GraphQL <br>
https://launchpad.graphql.com/new <br>
http://graphql.org/swapi-graphql/ <br>
 <br>
## Stackify Prefix
https://stackify.com/prefix/ <br>
http://demo.prefix.io/ <br>
 <br>
## RabbitMQ
https://customer.cloudamqp.com/login <br>
 <br>
### Publish messages:
curl -XPOST -d'{"properties":{},"routing_key":"my_queue","payload":"my body","payload_encoding":"string"}' https:/xyppsfen:7OPWvP2yHI6EDjbhUNOjvbcZpYwsUvxb@gopher.rmq.cloudamqp.com/api/exchanges/xyppsfen/amq.default/publish
 <br>
### Get messages:
curl -XPOST -d'{"count":1,"requeue":true,"encoding":"auto"}' https:/xyppsfen:7OPWvP2yHI6EDjbhUNOjvbcZpYwsUvxb@gopher.rmq.cloudamqp.com/api/queues/xyppsfen/my_queue/get <br>
 <br>
 <br>
 <br>
## AWS LAB:
https://run.qwiklabs.com/focuses/281?catalog_rank=%7B%22rank%22%3A2%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=2468535  - IAM <br>
https://run.qwiklabs.com/focuses/278  - S3 <br>
https://run.qwiklabs.com/focuses/284  - Lamda <br>
https://run.qwiklabs.com/focuses/269  - API Gateway <br>
https://run.qwiklabs.com/focuses/270  - CLoudfront <br>
https://run.qwiklabs.com/focuses/4088 - Lightsail, deploy LAMP <br>


