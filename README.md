## Hello

- This is just one useless utility
- You need to insert your API token, without this nothing will work
- `pip3 install --user -r requirements.txt`


## Tool output:

```shell
# python3 main.py -fn /var/log/nginx/[EDITED].ru/[EDITED].access_log
# python3 main.py -dn /var/log/nginx
# python3 main.py --help

➜  AbuseIPDB_checker git:(master) ✗ python3 main.py -f IPs.txt            
+-----------------+--------------+
| ipAddress       | totalReports |
+-----------------+--------------+
| 77.247.181.162  |     7161     |
| 185.220.100.253 |     2367     |
| 185.220.100.252 |     2200     |
| 23.129.64.100   |     2180     |
| 185.220.100.255 |     1926     |
| 51.77.135.89    |     1830     |
| 185.220.100.240 |     1295     |
| 185.220.100.243 |     1288     |
| 185.220.100.242 |     1285     |
| 185.220.100.245 |     1164     |
| 185.220.101.199 |     1135     |
| 185.220.101.5   |     1129     |
| 185.220.100.246 |     1071     |
| 185.220.101.195 |     1020     |
| 185.220.101.205 |     935      |
+-----------------+--------------+
```

## tips:
- support `xz` `gz`
