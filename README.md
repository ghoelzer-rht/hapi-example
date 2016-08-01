# hapi-example
Hapi.js Example for tutorial

Test API using the following command (assumes using local CDK with app name "hapi-example" and project "sample-node-app" .
Assumes default "mongodb" Service with MongoDB database name "api" and db user="user" and db password="password"

curl -i -X POST -H "Content-Type:application/json" hapi-example-sample-node-app.rhel-cdk.10.1.2.2.xip.io -d '{"message":"This is a test"}'
