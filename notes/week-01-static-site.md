## Lecture Notes:

- Create a simple static website and test it with `npx serve public`.
- Create a S3 bucket.
- Updload the static site to the S3 Bucket.
- Enable the Static Site Hosting on the S3 Bucket, keep the access private.
- Create a new Cloudfront Distribution (do not use the S3 Website prompt).
- Create the Cloudfront Origin Access Control Settings (Used Request Signing).
- Update the S3 Bucket policy as needed and prompted.
- Once deployed, test the URL from Cloudfront.

## Code:

- Created the code in [`/public`](../public/) directory.
