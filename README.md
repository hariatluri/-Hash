# Testcases /Hash

## Scenario 1 Application in a public S3 bucket.
"GIVEN when the application is launched with url in "https://s3.amazonaws.com/.....tgz"
THEN system downloads the application

## Scenario 2 Verify Password having Text ex:password":"angrymonkey"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 3 Verify Password having Number ex:password":"12345678"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 3 Verify Password having Negative Number ex:password":"-12345678"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 4 Verify Password having Special Charecter ex:password":"#$^%&&*(*)(*^%^%^%&^&^"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 5 Verify Password Boundary Limits(max and min charecters) ex:"password":"Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long textLong text Long text Long text Long textLong text Long textLong text Long textLong text Long text Long text Long textLong text Long textLong text Long textLong text Long textLong text Long textvLong text Long text Long text Long text Long text Long text Long text Long text Long text Long textLong text Long textLong text Long text Long text Long text"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 6 Verify Password having Empty space ex:password":"    "
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 7 Verify Password having NULL ex:password":NULL
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## DEFECT Malformed Input

## Scenario 8 Verify Password having no password ex:password":""
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password

## Scenario 9 Verify endpoint having Wrong port
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN Connection refused


## Scenario 10 Verify application should wait for http connection
"GIVEN when the application is launched after the port is set
THEN   Teminal keeps running


## Scenario 12 Verify Hashing Algorithm SHA512
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password
THEN Verify computed password is from  Hashing Algorithm SHA512

## Not able to verify

## Scenario 13 Verify /hash end points at the same time using &&
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash" && ""/hash"
THEN system wait's for 5 seconds
THEN computes and returns Encripted Password
