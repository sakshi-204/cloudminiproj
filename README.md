Working Link

http://simpleshop-sakshishinde.s3-website.ap-south-1.amazonaws.com/

# cloudminiproj
User fills form on website
        ↓
S3 (serves the HTML/JS)
        ↓
API Gateway (receives form POST)
        ↓
Lambda (Python code runs)
     ↙        ↘
DynamoDB     SES
(saves order) (sends email to you)
