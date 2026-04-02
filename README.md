Working Link

http://simpleshop-sakshishinde.s3-website.ap-south-1.amazonaws.com/

Working:
# cloudminiproj
User fills form on website<br>
<br>    <t> ↓<br>
S3 (serves the HTML/JS)<br>
  <br><t>      ↓<br>
API Gateway (receives form POST)<br>
<br><t>        ↓<br>
Lambda (Python code runs)<br>
<t>     ↙   <t>     ↘<br>
<br>DynamoDB   <t>  SES<br>
#(saves order) (sends email to you)
