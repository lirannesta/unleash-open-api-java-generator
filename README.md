# Read Me First
This project uses `SpringBoot` and OpenAPI Maven `openapi-generator-maven-plugin` plugin to generate Java classes for Unleash OpenAPI specification

# Getting Started
Inside pom.xml file, under openapi-generator-maven-plugin attributes, set the desired packages for API and model of the generated code.
Put the resource openAPI schema under /sec/main/resources/unleash.json (referenced already via the pom.xml file).
After cloning, run Maven clean + install.
The generated code will reside under /target/classes directory.
During Maven test phase, *UnleashOpenapiApplicationTests* will run , and load SpringBoot context. you can use these tests.  
One might also startup a SpringBoot Application using the already given *UnleashOpenapiApplication* class.  
  

### Reference Documentation


* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [OpenAPI Maven Plugin](https://github.com/OpenAPITools/openapi-generator/tree/master/modules/openapi-generator-maven-plugin)
* [Unleash API documentation](https://docs.getunleash.io/how-to/api)
* [Unleash OpenAPI reference](https://docs.getunleash.io/how-to/how-to-enable-openapi#location-of-the-openapi-spec)
