Edit this page to describe your Submission.

## Which Categories Best Fit Your Submission and Why?
Our submission would most likely fit “Best new feature”.

We believe that ASGARD will greatly benefit from the addition of Auto Scaling Group tags because of the additional flexibility provided to Netflix and the community as a whole.  

The use cases for resource tagging inside of EC2 are well documented and will empower a variety of users, while providing a base for future ASGARD improvements.

This feature was community requested and a production requirement for Juniper Networks (tags are used specifically for Puppet integration).

https://github.com/Netflix/asgard/issues/219

## Describe your Submission
Our submission is an enhancement for ASGARD.  

This enhancement provides the ability to create and edit tags for Auto Scaling Groups. 

Specific functionality is to add tags on ASG creation, add/edit/delete tags on existing ASG's, add/edit/delete tags on sequential ASG's, and view tags on rolling ASG's.

Client side validation is done to ensure tags and values are unique, and there are no more than 10 tags per ASG.


## Provide Links to Github Repo's for your Submission

https://github.com/shermdog/asgard/tree/prize-asg-tagging<br>
https://github.com/Netflix/asgard/pull/380


## Team
**The Baboon Crew**<br>
Rick Sherman @shermdog *leader<br>
Chris Guthrie @TheBaboon
