# IOpipe Java Agent

 * [Website](https://iopipe.com/)
 * [Repository](https://github.com/XerTheSquirrel/iopipe-java)
   * [Upstream Repository](https://github.com/iopipe/iopipe-java)
 * Language: **Java**
 * Duration: December 2017 to March 2019

The IOpipe Java agent allows you to measure and observe how your Java lambdas are running on [Amazon Web Services](https://aws.amazon.com/).

I developed the IOpipe Java agent which allows those who are using Java in AWS Lambda to view metrics on their invocations such as the duration of execution and errors. I implemented the agent along with its features such as profiling and logging following the direction of the other agents, which have previously implemented said features. I managed all of the project releases.

Any source code I wrote is fully documented with comments and is intended to be as concise as possible so that anyone, including myself, can go back into any part of the project and continue working on it. For each pull request made for any of the code that I write or have contributed to, I sometimes have paired with my manager to review that code. I have additionally created and/or reviewed other pull requests which were generally written in JavaScript, Go, and Python.

To ensure quality across the dashboard and the various agents I spearheaded what at the time was called QA Test Day which is a process that allows others to submit tasks to be tested along with general testing. I developed this process completely which includes how to submit tasks to be done and how to execute the tasks on the actual day in question. Other than QA Test Day, I regularly tested the dashboard and agents so that they can move into production.

While on the Engineering Team, I have been involved in a number of meetings on the architecture and direction of our product. My involvement in these meetings has never been specifically limited to my Java expertise, non-Java specific suggestions and thoughts have been iterated over and some of my ideas have been selected.

I have additionally written articles related to Java and AWS Lambda development on Medium. My most popular articles were Java Libraries are Your Lambda Enemy, and Optimizing AWS Java Lambdas, both of these are available in my list of publications.

# Articles

This is a listing of all the articles I have written while working at IOpipe, note that articles which are not specific to IOpipe are my most popular articles:

## Logging your Java Invocations with IOpipe

 * [View on Medium](https://medium.com/p/cec15bdaf562)
 * November 14, 2018
 * 99 views, 49 reads

> Want access to your AWS Java Lambda logs without leaving the IOpipe dashboard? We now support this in Java if you are using Log4j2 and TinyLog!

## Quick And Easy Observability for AWS Java Lambda, No Code Changes!

 * [View on Medium](https://medium.com/p/d6938c3e3e6f)
 * November 9, 2018
 * 124 views, 77 reads

> Now you can add observability to your AWS Java Lambdas using IOpipe without needing to modify any of your code! It just takes a few steps!

## Optimizing AWS Java Lambdas

 * [View on Medium](https://medium.com/p/3ea2b872fe74)
 * October 31, 2018
 * 3.7k views, 1.3k reads

> If your Java lambdas are running slow, it can be a nightmare to find the culprit! This article will cover a bunch of tried and true tips that you can utilize to optimize your code so that it runs faster, or uses less memory.

## Monitoring your Spring Cloud Function with IOpipe

 * [View on Medium](https://read.iopipe.com/monitoring-your-spring-cloud-function-with-iopipe-58c6ed624073)
 * September 13, 2018
 * 238 views, 79 reads

> If you use the Spring Cloud Function framework, you can monitor executions of it using IOpipe. Starting with version 1.8.0 of the IOpipe Java agent you are able to wrap Spring Cloud Functions using the Generic Entry Point handler without making any modifications to your code!

##  Java Libraries are Your Lambda Enemy

 * [View on Medium](https://read.iopipe.com/java-libraries-are-your-lambda-enemy-6c9467321d2b)
 * August 23, 2018
 * 7.6K views, 2.9K reads

> So you are using AWS Lambda and your invocations seem to be running a bit slow, especially in the cold start area. Have you ever thought that this is caused by the libraries you are using? Java can be expensive on AWS Lambda, but it does not have to be at all.

# Recommendations Received

## Adam Johnson (CEO of IOpipe)

> Stephanie worked with us at IOpipe to build out our Java instrumentation library for AWS Lambda based serverless applications.  She built out the library from scratch and was very self driven the entire time. Throughout the project, Stephanie delivered incredibly high quality code.  She has deep knowledge of Java and and the JVM, and was able to solve numerous technical hurdles with the project.   Stephanie was able to work autonomously on the project with little oversight, while keeping the quality and attention to detail high.
> 
> If you're looking for a self driven engineer to work on any complex Java/JVM based work, look no further. 

## Pam Selle (Direct Manager)

> I worked with Stephanie on a project that was not only critical to our business, but where the source code would be open sourced, no small matter. Stephanie took direction well, received feedback very well, and was very responsive during the entirety of the project. I knew that when I asked Stephanie to work on something, or gave feedback for modifications, I could trust her to execute on it and she'd promptly let me know when things were ready for re-review. She worked well within our process, and I'd recommend working with her.

## Erica Windisch (CTO of IOpipe, Direct Manager)

> Stephanie is a fast and efficient developer that has exceeded our expectations. I began working with her when she was a junior engineer, but she quickly began solving difficult and complex problems as well as any of our senior staff.
