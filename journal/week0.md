# Week 0 — Billing and Architecture
## Homework



### Architecture in Lucichart

[Let's see it](https://lucid.app/lucidchart/ced94c16-77ec-47c1-abc5-675eac3eb8ef/edit?viewport_loc=-393%2C-204%2C3897%2C1944%2C0_0&invitationId=inv_335dd30a-6d0f-4b6b-b53b-3c6757f8b630). 


### Create an Admin User

### Use CloudShell

### Generate AWS Credentials


### Installed AWS CLI

I previously installed it and use this reference to install it

![aws](assets/aws-cli.png)


https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Step 1 

```
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
```

Step 2 

```
sudo installer -pkg ./AWSCLIV2.pkg -target /
```

Step 3

```
which aws

/usr/local/bin/aws 

aws --version
```


### Gitpod 

I installed the extension .

but for some reason when I try to open Gitpod , in the page show me I already have a email for github .
for this reason I use my local repo with VS code

I will try to fix it soon ... 

![Gitpod Error](assets/aws-cli.png)

![Shell](/assets/shell.png)

### Create a Billing Alarm



### Create a Budget

I create the budget via GUI but i can see the information via CLI with this command.

aws budgets describe-budget --account-id 038306313412 --budget-name "Budget Bootcamp AWS"

