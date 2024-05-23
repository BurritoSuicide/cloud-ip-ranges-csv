# cloud-ip-ranges

Forked from femueller, this repo will contain major cloud provider IP ranges formatted in CSV and cleaned up.

## Data sources

* Amazon Web Services (AWS) - https://ip-ranges.amazonaws.com/ip-ranges.json
* Cloudflare
    * IPv4 - https://www.cloudflare.com/ips-v4
    * IPv6 - https://www.cloudflare.com/ips-v6
* DigitalOcean - https://digitalocean.com/geo/google.csv
* Google Cloud - https://www.gstatic.com/ipranges/cloud.json
* Oracle Cloud - https://docs.oracle.com/iaas/tools/public_ip_ranges.json
* Linode - https://geoip.linode.com/

### Missing data

* Azure - https://docs.microsoft.com/en-us/azure/virtual-network/public-ip-addresses
* Tencent Cloud (https://www.ip2location.com/as133478)
* Alibaba Cloud (https://udger.com/resources/datacenter-list/datacenter-detail?name=alicloud) - Best I could find, contains most.

### To Do

* Make a script that converts all JSON files to CSV. Unfortunately most json's are formatted differently and requires different code.
