<script crossorigin="anonymous" src="https://unpkg.com/launchdarkly-js-client-sdk@2.18.1"></script>

<h1>Great LinkedLn Courses</h1>

https://www.linkedin.com/learning/git-for-teams

Development teams transitioning to distributed source control with Git often experience friction when initially adopting
the tool. Often, the root cause is related to issues surrounding culture and practices as opposed to a technical
learning curve. In this course, Kevin Bowersox covers collaboration strategies for teams using Git, discussing tools and
techniques that can help you and your team circumvent the challenges that hinder the delivery of high-quality software.
Kevin shares best practices and tips that can help you avoid common pitfalls that often cause teams to veer off track.
Learn branching strategies, how to build a continuous integration pipeline, ways to maintain your workflow, and more.

https://www.linkedin.com/learning/building-apis-with-swagger-and-the-openapi-specification

The Swagger platform offers a rich ecosystem of tools that developers can use to create well-crafted APIs that boast
higher adoption rates. Curious about how to leverage Swagger in your workflow? In this course, learn how to build and
document high-quality APIs with Swagger and the OpenAPI Specification. After going over the basics of the Swagger
ecosystem, instructor Kevin Bowersox shows how to build API definitions that speed up the delivery of APIs using the
OpenAPI Specification. He also shows how to create and publish APIs with SwaggerHub, an integrated API development
platform. To wrap up, Kevin steps through a hands-on project that shows you how to plan API development for
applications.

https://www.linkedin.com/learning/building-apis-with-swagger-and-the-openapi-specification

The Swagger platform offers a rich ecosystem of tools that developers can use to create well-crafted APIs that boast
higher adoption rates. Curious about how to leverage Swagger in your workflow? In this course, learn how to build and
document high-quality APIs with Swagger and the OpenAPI Specification. After going over the basics of the Swagger
ecosystem, instructor Kevin Bowersox shows how to build API definitions that speed up the delivery of APIs using the
OpenAPI Specification. He also shows how to create and publish APIs with SwaggerHub, an integrated API development
platform. To wrap up, Kevin steps through a hands-on project that shows you how to plan API development for
applications.

<div id="preview" style="display: none">
https://www.linkedin.com/learning/calling-rest-apis-with-java

Get the information you need on several popular third-party REST APIs, including the Azure Cognitive Services API, the
Twitter API, the Twilio API, and more. Instructor Kevin Bowersox shows you how to call these APIs, using various
techniques available in Java. Kevin uses each chapter to focus on a specific third-party API and a specific Java tactic
for calling the API. Within each chapter, he goes over the purpose of the API, its major resources, and its security
scheme, then he provides hands-on lessons that demonstrate how to call the API. Kevin demonstrates how to interact with
these APIs, so you can get hands-on experience working with real world APIs that will translate to other APIs that you
can leverage in your professional development.
</div>

<script>

var clientId='66b32bb9bd42920fe6ba0c6b',
flagName='course-preview',
user={anonymous:true},
ldClient = window.LDClient.initialize(clientId, user);


ldClient.on('ready', function () {
  document.getElementById("preview").style.display=ldClient.variation(flagName, false)?"block":none;
});

ldClient.on('change:'+flagName, function (newVal, prevVal) {
  document.getElementById("preview").style.display=newVal?"block":none;
});



</script>