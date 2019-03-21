## Nanotwitter

A baby twitter.

http://nanotwitter.us-east-2.elasticbeanstalk.com/

### Contributors
- Xiangran Zhao
- Julian Ho
- Aaron Gold

## Changes

### 0.5 (3/18/19)

- Finalized all routes and models and insured that functionality is accurate
- Reworked follows and built routes for users, tweets, follows
- Implemented seed data using activerecord import
- Created tests for users, tweets, and follows
- Worked on further AWS deployment, docker
- Implemented EB, codePipeline/codeDeploy, and AWS RDS
- Added monitoring capability via AWS CloudWatch


### Steps to run

```
bundle install

rake db:create

rake db:migrate

```

Optional: rake db:seed

Tests can be ran by running:
```ruby test/test.rb```

Seed data can be run by running
```ruby db/seed.rb```
