# circleci-excercise

The base of this code is from a Udemy course by Andrei Neagoie where he is teaching React. I implemented the CI process into this code by using Circle Ci. Circle Ci takes cares of building the code and running tests. Continues deplpoyment is also implemented here by connecting the repository to Github pages where the website is availabe: https://pauneren.github.io/circleci-excercise/.

The configuration of the CI process can be found on the .yml file here: https://github.com/Pauneren/circleci-excercise/blob/main/.circleci/config.yml In that configuratin is the defintion of a workflow that arranges the steps of the CI process. Here the steps constist of building the project and running automated testing. It is possible to add many different steps here also like checking the filesize of the javascript files and other useful checks but non of that is implemented here.

I built the .yml file and changed it many times until it passed the testing. The tests I did are here https://app.circleci.com/pipelines/github/Pauneren?invite=true In order to access to the circleci project you need to accept the invitation to this project on github

I also did something interesting by putting a pre-commit hook that runs prettier before every commit and prettifies the code automatically. The documentation on how to do this can be found here: https://prettier.io/docs/en/precommit.html.

It is very nice to learn here the best practices of coding in teams where Pull Requests can be used both to ensure code quality by having team members reviewing each others work and also getting them better involved in code changes.
