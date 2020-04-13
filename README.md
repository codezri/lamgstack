# LAMG
### World's cheapest but modern stack for lightweight web apps

## What is LAMG?

LAMG (stands for Lambda Angular Mongodb Github) is a full-stack solution which helps you develop or prototype lightweight, maintainable and less-complex web applications. The key goal of LAMG is to offer you a solution stack which has absolutely zero cost specially targeting application prototyping, pilot apps and for production use cases.

## LAMG Components 

**L - AWS Lambda**

Back-end business logic will be implemented in seperate Lambda functions using your favourite programming language(Eg- Javascript). Lambda services will be exposed to outside world via AWS API Gateway.

**A - Angular**

Front-end of the solution will be implemented with Angular which is very nice framework with all things we need. Feel free to use any kind of UI library such as bootstrap, material etc.

**M - Mongodb**

If you need persistant service to store data, LAMG suggests to go ahead with small online Mongodb instance which is free.

**G - Github**

Your client will be deployed into Github pages which is abosultely free. Additionally, since it is Github you will have free github.io subdomain, Github actions, source code management services too.

## Get started!

**STEP 1**

Create a repository on Github and enable pages feature for `gh-pages` branch.

**STEP 2**

Create new Angular app and install [angular-cli-ghpages](https://github.com/angular-schule/angular-cli-ghpages) as a global module.

**STEP 3**

Sign up with AWS and create lambda functions as you wish. Eventually, make sure to expose those via API gateway. If your backend has multiple functions use [Serverless framework](https://serverless.com/).

**STEP 4**

If you need to persist your data signup and get free 512MB instance on [Mongodb cloud](https://www.mongodb.com/cloud/atlas).

**STEP 5**

Once everything is set, deploy the client using, 
```
$ ng deploy --base-href=/the-repositoryname/
```

## Example apps built with LAMG stack

- [movieszri](https://codezri.org/movieszri/)
- Did you build your app with LAMG? Send us a pull request!


*P.S: Don't confuse with the word stack which refers on top of like, this solution is very much distributed over monolithic*
