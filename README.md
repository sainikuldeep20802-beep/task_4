# task_4
step1: create a new function with basic lambda permission.
<img width="1918" height="1132" alt="lambda function" src="https://github.com/user-attachments/assets/c1c4fbd8-1420-4e6e-a5a2-fa400fae1cf3" />
step2: create a code file.
[lambda_function.py](https://github.com/user-attachments/files/23120686/lambda_function.py)
step3: deploy successfully deployed in aws.
<img width="1918" height="1147" alt="successful_deployment" src="https://github.com/user-attachments/assets/d7eb2800-8f4e-454d-a841-0684927cc96a" />
step4: Run from a weblink.
https://rv9ancw6j7.execute-api.us-east-1.amazonaws.com/default/my-function-kul
       serverless function working on the internet.
then clean up the lambda function.


An overview of how lembda function work?
 The AWS Lambda function runs automatically in response to an event — in this case, an HTTP request from API Gateway.
When someone opens the function’s URL, API Gateway sends the request to Lambda.
Lambda runs the Python code inside the function (lambda_handler) and returns a response message (for example, “Hello from my first AWS Lambda Function!”).

No servers need to be created or managed — AWS automatically handles scaling, execution, and billing only for the time the function runs.
This shows the concept of serverless computing and Function-as-a-Service (FaaS).
