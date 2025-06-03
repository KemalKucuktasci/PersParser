# PersParser
This projects used to create an output document from given scripted text document. 
Receive some delimited text scripts and replaced by desired value and craete an output.

It is used to otomated systems document generater.

for example the source text is:

    Sample text document
    [[variable1]]
    plase confirm.

after an operation variable1 in previous document replaced by desired value. For this example variable1 hold a date value from DB. 
"01/01/2025 18:56:25" generated value is

    Sample text document
    01/01/2025 18:56:25
    please confirm.

This type of operation can be used so many operations.  
1. Generating HTML Mail from an template
2. Generation Text value for sending SMS
3. Generation new JSON value to store or communicate with services as in body
4. etc.

