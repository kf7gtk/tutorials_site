# Intention

This is intended to become a serverless, rust-driven website. It will likely be deployed on AWS Lambda.

I plan to use this site to publish multiple tutorial series covering topics in math, IT, and programming.

# Roadmap

1. Make a minimum viable site with axum
      - Make a sitewide template
      - Subtemplate for courses, to be inserted into the sitewide template
      - Each chapter is its own file to be inserted into the course subtemplate
      - Create content for a basic homepage
2. Update project to use axum-aws-lambda
3. Implement SSL
4. Publish and maintain online, domain name TBD
5. Create a multiple choice quiz system
      - Allow constants to be randomized in math problems
6. Implement an explanation feature on the quiz system
      - Inlude a way to automatically solve math equations with randomized constants
7. Go ham making tutorial content
