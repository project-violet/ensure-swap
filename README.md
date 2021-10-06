# ensure-swap

https://support.hpe.com/hpesc/public/docDisplay?docId=kc0101059ko_kr&docLocale=ko_KR

```
mkdir -p /var/swap
dd if=/dev/zero of=/var/swap/swapfile bs=1M count=1000
mkswap -f /var/swap/swapfile
swapon /var/swap/swapfile
swapon -s
```

```
swapoff /var/swap/swapfile
```
