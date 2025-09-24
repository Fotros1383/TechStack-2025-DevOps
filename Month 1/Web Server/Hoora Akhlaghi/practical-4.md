
# 1) install nginx

![](./images/1-install_nginx.png)
![](./images/2-test_nginx.png)

# 2) serve a static site with nginx

![](./images/3-config-to-show-my-html.png)

![](./images/4-test-change-default_page.png)

# 3) reverse proxy

![](./images/5-reverse-proxy-config.png)

![](./images/6-reverse-proxy-test.png)


# 4) Load Balancing

از round-robin استفاده کردم که ملموس تر باشه توی مثال ساده که چطور بین سرور ها سوییچ انجام میشه.

و اینکه با اینکه می بردم توی بک گراند دو تا بک اند را نشد که دوتاش روی یه ماشین باشه و درست نمی شد سوییچ بینشون(نمی دونم چرا :))
برای همین یکیش را روی اوبونتو سرور و یکی را روی سیستم خودم ران کردن و ایپی سیستمم را به عنوان یکی از سرورها دادم.


![](../images/7-test_load_balancing-1.png)
![](../images/7-test-load-balancing-2.png)
![](../images/8-config-for-load-balancing.png)

# 5) Authentication

![](../images/9-add_user.png)

![](../images/10-test.png)

![](../images/11-config.png)
