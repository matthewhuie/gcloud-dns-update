# gcloud-dns-update
Automate your Cloud DNS record updates

## Getting Started
Run this shell script stand-alone or via crond. Ensure that you specify the following parameters within the script:  

`USER_GCLOUD_AUTHED` - the local user authenticated with gcloud  

`DNS_ZONE` - the DNS zone to configure  

`DNS_RECORD_NAME` - the DNS record name to update  

`DNS_RECORD_TYPE` - the DNS record type to update  

`DNS_RECORD_TTL` - the DNS record TTL to update  

`PATH_TRANSACTION` - the path of the gcloud transaction YAML (default: /tmp)  
