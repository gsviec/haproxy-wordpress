##
Trong hướng dẫn này chúng tôi sẽ huớng dẫn các bạn cách tạo và mở rộng website chạy wordpress, có khá là nhiều công cụ giúp cân bằng tải(loadbalancer) như HAProxy, Nginx, LVM,... nhưng trong huớng dẫn này tôi sẽ huớng dẫn các bạn cách dùng HAProxy


Xem thêm tại đây https://gsviec.com/blog/cau-hinh-load-balancing-cho-wordpress

### Cài đặt

```
ansible-playbook -i hosts playbook.yml
#ansible-playbook -i hosts --limit=db  playbook.yml

```