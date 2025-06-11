# fit5225---assignment-2---solved
**TO GET THIS SOLUTION VISIT:** [FiT5225 – Assignment 2 – Solved](https://mantutor.com/product/fit5225-assignment-2-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90230&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;FiT5225 -  Assignment 2 - Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<strong>TagTag:A Modern Image Storage on the Cloud</strong>

<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Synopsis</h1>
This assignment aims at building a cloudified online system that allows users to store the images and retrieve the images based on the auto-generated tags. The focus of this assignment is to design a serverless application that allows the client to upload their images to public cloud storage. Upon the image upload, the application automatically tags the image with the type of objects detected in it, for example, person, car, etc. Later on, clients can query images based on the type of objects in the images. To this end, the application provides users with a list of URLs for images that include specific queried objects.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Group Assignment</h1>
Majority of software developers will work in a team at a certain point in their career. Hence, to prepare the students to experience software development as a team, this assignment is designed as a group project. Students will be put into software teams to work on the implementation of the system described above. Each team will have up to 4 students. In this assignment, students need to organise their team and their collective involvement. There is no team leader as such, but teams may decide to set up processes for agreeing on the work and who does what. Understanding the dependencies between individual efforts and their successful integration is key to the success of the work and for software engineering projects more generally. If teams have “issues”, then please let the lecturer know asap and help will be provided to resolve them. We will evaluate your involvement in the project individually and if you fail to satisfy your tasks within the team you might be penalised heavily irrespective of your project success.

<h1>3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Assignment</h1>
Teams should develop an AWS Cloud-based solution that exploits services such as S3, Lambda, API Gateway and database service (e.g. DynamoDB) to build a system for automated object-detection tagging and query handling. The teams should produce a solution that allows end-users to upload their images into an S3 bucket. Upon uploading of an image to a designated S3 bucket, a lambda function is automatically triggered that uses the Yolo object detection feature and finds the list of objects in the image and stores the list of detected objects along with the URL of the image (S3 URL) in a database. Further, the end-user should be able to submit queries to an API endpoint using API Gateway to search tagged images (more details to come). Table 1 provides a glossary of terms used in the assignment description.

<h2>3.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Authentication and Authorisation</h2>
Security is one of the most important aspects of developing cloud-first applications and when your application is publicly exposed, you need to ensure that your endpoints and resources are safeguarded against unauthorised access and malicious requests. AWS, via its Cognito service, provides an easy, secure, and centralised approach to protect your web application and its various resources from unauthorised access.

Table 1: Glossary of terms

<table width="539">
<tbody>
<tr>
<td width="182"><strong>Term</strong></td>
<td width="356"><strong>Meaning</strong></td>
</tr>
<tr>
<td width="182">team</td>
<td width="356">A group of 4 students who are doing the project</td>
</tr>
<tr>
<td width="182">queries</td>
<td width="356">You will implement multiple APIs to query different information including a request message by the end user to find list of images with specific tags, find images with similar tags of an image, update tags of an image, and delete record of an image.</td>
</tr>
<tr>
<td width="182">tags</td>
<td width="356">list of objects detected in an image, e.g., person, car, and cat.</td>
</tr>
<tr>
<td width="182">federated authentication</td>
<td width="356">Federated authentication is a Single sign-on (SSO) mechanism that allows you to use authentication credentials of external identity providers such as Google or Facebook to access your AWS services such as Lambda, S3 or DynamoDB.</td>
</tr>
<tr>
<td width="182">Peer assessment</td>
<td width="356">Each team member is expected to complete a <strong>confidential </strong>report and evaluation on his/her role in the project and the experiences in working with other team members on the demonstration day.</td>
</tr>
</tbody>
</table>
To leverage the AWS Cognito service, first you need to create a <strong>user pool </strong>that persists user credentials. Then you need to create and configure a client app that grants access to your application and/or other AWS services to query and use the user pool. Finally, you have two options to communicate with the AWS Cognito service and perform authentication and/or authorisation: 1) Use AWS Amplify JavaScript Library to bootstrap the authentication module of your application 2) Use AWS JavaScript SDK to access the user pool and identity provider(s) that you have defined earlier.

Your application should support the following workflow and features:

<ul>
<li>Detect whether a user is authenticated or not. If the user has not signed in, access to all pages/endpoints except the sign-up service needs to be blocked and the user should be redirected to “sign-up.html” page to register a new account. For each new account, you need to record user’s <em>email address</em>, <em>first name</em>, <em>last name</em>, and <em>password</em>. Cognito will take care of sending an email to new users and asking them to verify their email address and change their temporary password.</li>
<li>Your application should have a login page that allows users to sign-in. Upon successful authentication, the user should be able to upload images, submit queries, view query results, and sign out of the application. All these services need to be protected against unauthorised access. You can either use Hosted UI feature of Cognito to implement login and sign-up web pages or create your own version and call Cognito APIs.</li>
<li>Uploading files to an S3 bucket, invoking Lambda functions to execute the business logic of your application, and accessing the database for data storage and retrieval, all require fine-grained access control permissions that you need to set up via IAM roles and appropriate policies.</li>
</ul>
As an <strong>optional </strong>feature, you can add federated authentication using AWS Cognito Identity Pools to your application and earn bonus marks (up to 5 points shall be awarded if you add federated authentication to your project). For this purpose, you need to create a Facebook or Google app that serves as an external identity provider and authenticates users on behalf of your application, then forwards authentication tokens to your application. Note that having external authentication providers in your project is <strong>not </strong>mandatory.

Since federated authentication might be challenging, I <strong>strongly </strong>recommend you to finish the requirement of the assignment first; then if you have extra time, work on this feature.

<h2>3.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Image Upload</h2>
Your solution should provide a mechanism to upload an image to an S3 bucket. Uploading an image to an S3 bucket can be done either through an API Gateway endpoint (POST REST APIs) call or it can be done directly using AWS SDKs (for instance, boto3 if you are using Python). Whenever an image is uploaded to the S3 bucket, your system must trigger an event and thus invoke a Lambda function.

You are expected to configure the triggers, and grant required Amazon resource permissions (execution roles) for the Lambda function. The Lambda function should read the uploaded image and detect objects in the image and save the list of detected objects (we call them tags) along with the S3-url for that image in an AWS database for future queries. Please be advised that you should update your Yolo script that you have be given in your first assignment to suit with the AWS Lambda function. This includes removing any FLASK related code, incorporating Lambda function and required libraries to read the image from s3 buckets, storing s3-url and tags in the database. You may create a separate s3 bucket to store the yolo and other config files which can be referenced in your lambda function. You might also ignore detected objects with an accuracy of detection below a specific threshold (e.g., 0.5). Please note that <strong>Amazon Rekognition </strong>is specialised AWS service for identification of objects in images and can be used instead of Yolo. However, in this assignment, you are <strong>not </strong>allowed to use Amazon Rekognition service.

<h2>3.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Queries</h2>
Your solution should provide APIs which allow following queries.

<ol>
<li><strong>Find images based on the tags</strong>: The user can send a text-based query to request URLs of images that contain specific tags (e.g., person, person and car, person and desk and cat). You are expected to create an API Gateway with a RESTful API that allow users to submit their requests, e.g., GET or POST requests. Your application might send a list of tags via certain GET parameters through the requested URL, for example:</li>
</ol>
https://jyufwbyv84.execute-api.us-east-1.amazonaws.com/dev/search?tag1=cat&amp;tag2=car

or it can be a POST request with a JSON object including a list of tags. A sample JSON object for a query request is given below:

{

“tags”: [

“person”,

“desk”, …

“cat”

]

}

A response should include the list of URLs to all images that contain all the requested tags in the query. This can be a JSON message similar to the following:

{

“links”: [

“https://tagtag.s3.amazonaws.com/image1.png”,

“https://tagtag.s3.amazonaws.com/image59.png”,

“https://tagtag.s3.amazonaws.com/image180.png” ]

}

Your query may require to trigger one more Lambda function that receives a list of tags and finds s3-url of images containing <strong>all tags in the query </strong>from the database.

Please note that duplicate tags should not affect the results. This means a query with

{“tags”:[“person”,”person”]} results in the same response as {“tags”: [“person”]}.

<ol start="2">
<li><strong>Find images based on the tags of an image</strong>: The user can send an image as part of an API call. The list of all objects (tags) in the sent image is discovered and then all the images in TagTag storage containing those set of tags are found. Finally, as a response, the list of URLs to matching images (similar to the above query) are returned to the user. You should make sure that the image uploaded for the query purpose is not added to the database or stored in s3. Similar to previous query, duplicate tags would not affect the results.</li>
<li><strong>Add extra tags to an image</strong>: Your solution should also provide an API that the end-user can add extra tags to an image. You are expected to create an API Gateway with a POST API that allow users to submit their requests to add extra tags to an image.</li>
</ol>
A sample JSON message sent to the API is:

{

“url”:”https://tagtag.s3.amazonaws.com/image1.png”, “tags”: [

“person”,

“alex”

]

}

This request adds “person” and “alex” to the tag list of the image in the URL:

https://tagtag.s3.amazonaws.com/image1.png.

This can be done through a Lambda function to update the entry in the database.

<ol start="4">
<li><strong>Delete an image: </strong>The user can communicate the URL of an image to an API and the system should remove the image from s3 and relevant entries from the database.</li>
</ol>
<h2>3.4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; User Interface</h2>
You can design a simple user interface (UI) (We suggest web-based. But it can be any form of UI) that includes the following pages: login, sign-up, upload images, submit queries, and view query results. A UI makes your system easier and more enjoyable to use. However, you have the option not to create a UI for application or have UI for some parts and not the others. If you opt to ignore UI or full-fledged UI, you can write scripts (e.g., Python) to handle communications with your application APIs. Please be aware that you might need to manually copy credentials provided by the identity pool to your scripts each time if you choose to work with the second option.
