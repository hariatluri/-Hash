# Testcases
## Scenario 1 Application Launched and Port is set
"GIVEN when the application is launched
THEN port is set"

## Scenario 2 Verify Password having Text ex:password":"angrymonkey"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

## Scenario 3 Verify Password having Number ex:password":"12345678"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

## Scenario 3 Verify Password having Negative Number ex:password":"-12345678"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

## Scenario 4 Verify Password having Special Charecter ex:password":"#$^%&&*(*)(*^%^%^%&^&^"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

## Scenario 5 Verify Password Boundary Limits(max and min charecters) ex:"password":"Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long text Long textLong text Long text Long text Long textLong text Long textLong text Long textLong text Long text Long text Long textLong text Long textLong text Long textLong text Long textLong text Long textvLong text Long text Long text Long text Long text Long text Long text Long text Long text Long textLong text Long textLong text Long text Long text Long text"
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

## Scenario 6 Verify Password having Empty space ex:password":"    "
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password


## Scenario 7 Verify Password having NULL ex:password":NULL
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

## Scenario 7 Verify Password having no password ex:password":""
GIVEN when the application is launched
WHEN port is set
WHEN  Enter the POST endpopint with password in the Terminal "/hash"
WHEN wait for 5 seconds
THEN computes and returns Encripted Password

