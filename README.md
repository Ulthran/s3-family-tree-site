# s3-family-tree-site

A simple template for a static S3 site to display a family tree using [BALKAN FamilyTreeJS](https://balkan.app/FamilyTreeJS). Mine is running [here](http://bushman-family-tree.s3-website-us-east-1.amazonaws.com/) for an example.

# Setup

 - Clone this repo and create a copy of `example_members.js` called `members.js`; then fill in `members.js` with your family data following the example JSON structure
 - Follow [this](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html) AWS guide to create a static S3 website
 - Once you get to the step for configuring an index document, just upload all the files in this repository into your S3 bucket
 - At this point you should be good to go; local testing and development is easy, just open index.html in a browser; to update the site just upload any modified files to the bucket
 - Now comes the hard part of finding and filling in meaningful data; good luck!
