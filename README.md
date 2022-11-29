# Hash Length Extension Attack

I came across this attack while doing the Code Review badge on Pentester Lab. It was a Python code snippet using Flask framework which  redirected a payment made by the user by creating a signature for the payment information. The signature is created using SHA-256. 