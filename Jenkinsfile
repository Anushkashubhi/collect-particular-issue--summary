pipeline{
agent any
stages{

stage('Jenkins job'){
steps{
 
sh '''
   curl -X GET \
  'http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/api/2/search?jql=issue%3DAVR-4&fields=key%2Csummary%2Cdescription' \
  -H 'accept: application/json' \
  -H 'authorization: Basic cmlnOmRpZ2l0YWxyaWdAMTIz' \
  -H 'cache-control: no-cache' \
  -H 'postman-token: b2daa8ca-5051-ac89-1355-078f25c10d07'
  '''
  }
  }
  }
  }


