About Cacert.pem

The code as it stands is configured to be run on localshost. If used on a production server, all references to cacert.pem need to be removed.
This means that many functions in crmUploaderFunctions.php will have one less argument in the parameter list.
Cacert.pem is used to provide the necesssary certificate to enable SSL on localhost.
