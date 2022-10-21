# Honkit S3 Template

Launch your customizable website in 5 minutes!!!

# Setting

1. create new repository using this template.
2. setup AWS credential in github secrets. The credential should have priviladge of `AmazonS3FullAccess` & `AWSCloudFormationFullAccess`.
3. setup environment value in `.github/workflows/deploy-s3.yml` & `.github/workflows/create-s3.yml`.
4. run `create s3 stack` workflow in github actions.
5. check s3 public URL on AWS S3 console, and set your DNS as `CNAME` value.
6. go your website!!!
7. (optional) comment out `push` trigger in `.github/workflows/deploy-s3.yml`.

# Customizing

see `honkit` documentation. Honkit has a lot of plugins, and you can create one.
https://honkit.netlify.app/
