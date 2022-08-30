

Terraform Take Home AssignmentnGuide
● We encourage you to write the code to be production ready.
● Consider all questions as a green field project that you can design as you want.
● You should store each answer in a dedicated directory following the pattern
questions/[question number]/[files].
● Estimated time for this project 3-6 hours.

Questions
1. Random Public IP
One of our applications runs on a site that has no fixed Public IP. We have a pipeline that
runs terraform periodically and updates the firewall rule that allows access from this
application to our main Cloud Provider.
You've been tasked with to code a terraform module that outputs the outgoing IP
address of this server.
Note: You can assume that the pipeline runs from the same server as the application.
2. Modules dependency
You should create a terraform module that receives a string as input and outputs the
message received. Then, your main file should call the module twice with the following
messages, respectively:
- "I am message one"
- "I am message two"
The modules should be executed in order and the messages printed with double quotes.
3. Testing your code
Write any terraform code with a minimum of three resources including tests.