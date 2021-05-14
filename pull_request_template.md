# What & why

*Explain what change this PR represents and reference a JIRA ticket if appropriate (don’t just reference the ticket though). What is the wider effect of this PR?
e.g I have added a new lambda to the nat-strata that does X - this is to allow us to automate Y which is further documented in <JIRA>. This is integrated by changing X which can be see in PR #102 which will effect anyone in the VPC because Z.*

# How

*The diff will tell most of the story of the “how”, but make sure to draw attention to the significant design decisions and what led you to make them.
e.g Added a new lambda construct which uses the CDK Dockerised Lambda resource type. Used to docker approach here to be consistent with the rest of our repositories and improves dependency management.*

# Testing

*What testing did you do? Did you add unit/integration tests - if not, why? If more manual testing was required, include steps on how to reproduce.
e.g Added unit tests for the lambda, deemed sufficient to cover the minimal complexity added. Successfully diffs with cdk diff.*

# Anything else?

*Any additional information that might help the reviewer understand the choices in the ticket. You can also add inline comments to the code if it will help.*
