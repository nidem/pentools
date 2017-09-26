# pentools

## GetCertNames:

Takes targets (-t) in IP, FQDN, or CIDR format and combines them with ports (-p) and extracts the CN and the Subject Altrnate Names from the certificate. By default, the script will randomize the host and ports but it can be disabled with -r. The -v option can be used to show the verbose actions.