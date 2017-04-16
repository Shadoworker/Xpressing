Sample Application with Gradle and Grails 3
===========================================

Running Locally
---------------

First, you need to have a working grails environment: http://docs.grails.org/latest/guide/gettingStarted.html#requirements

Then, simply execute:

```sh
grails run-app
```

Deploying on Scalingo
---------------------

Create an application on https://scalingo.com, then:

```
git remote add scalingo git@scalingo.com:<name_of_your_app>.git
git push scalingo master
```

And that's it!

The application is running at this url: https://sample-java-grails3.scalingo.io/

Deploy in one click
-------------------

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy)

