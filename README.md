# Fail2Ban Filter for [Pancake App](https://www.pancakeapp.com/ref/5UCrtz)

Please checkout my blog [TechTutes.net]() for full tutorial. 

### Fail2Ban - jail.local

In debian `/etc/fail2ban/jail.local`

```[pancake]  
enabled  = true  
port   = http,https  
filter = pancake  
logpath  = /var/log/auth.log  
maxretry = 3```

### Filter

Copy paste the filter to `/etc/fail2ban/filter.d/` directory.


