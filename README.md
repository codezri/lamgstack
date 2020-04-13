# LAMG
### World's cheapest but modern stack for lightweight web apps

## What is LAMG

LAMG (stands for Lambda Angular Mongodb Github) is full stack solution stack which helps you develop or prototype lightweight, maintainable and less-complex web applications. The goal of LAMG is to offer you a solution stack which has absolutely zero cost specially tartgeting application prototyping and pilot apps.

## Components 

**L - AWS Lambda**

Back-end business logic will be implemented in seperate Lambda functions using your favourite programming language(Eg- Javascript). Lambda services will be exposed to outside world via AWS API Gateway.

**A - Angular**

Fron-end of the solution will be implemented with Angular which is very nice framework with all things we need. Feel free to use any kind of UI library such as bootstrap, material etc.

**M - Mongodb**

If you need persistant service to store data LAMG suggests to go ahead with online mongodb instance which is free.

**G - Github**

Your client will be deployed into Github pages which is abosultely free. Additionally since it is Github you will have free github.io subdomain, Github actions, source code management services too.

## Get started!

**STEP 1**

Create a repository on Github and enable pages feature for `gh-pages` branch.

**STEP 2**

Create new Angular app and install [angular-cli-ghpages](https://github.com/angular-schule/angular-cli-ghpages) as a global module.

**STEP 3**

Sign up for AWS and create lambda functions as you need. Eventually make sure to expose those via API gateway. If your backend has multiple functions use [Serverless framework](https://serverless.com/);

**STEP 4**

If you need to persist your data signup and get free 512MB instance on Mongodb cloud.

**STEP 5**

Once everything is set, deploy client using 
```
$ ng deploy --base-href=/the-repositoryname/
```

## Example apps built with LAMG stack

- [movieszri](https://codezri.org/movieszri/)
