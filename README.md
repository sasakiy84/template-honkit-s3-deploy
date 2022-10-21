# Honkit S3 Template

Launch your customizable website in 5 minutes!!!

# Setting

1. Create new repository using this template.
2. Setup AWS credential in github secrets. The credential should have privileges of `AmazonS3FullAccess` & `AWSCloudFormationFullAccess`.
3. Setup environment value in `.github/workflows/deploy-s3.yml` & `.github/workflows/create-s3.yml`.
4. Run `create s3 stack` workflow in github actions.
5. Check s3 public URL on AWS S3 console, and set your DNS as `CNAME` value.
6. Go your website!!!
7. (Optional) Comment out `push` trigger in `.github/workflows/deploy-s3.yml`.

# Customizing

see `honkit` documentation. Honkit has a lot of plugins, and you can create one.

https://honkit.netlify.app/
