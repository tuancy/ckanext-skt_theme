Phiên bản giao diện này chạy ổn định trên ckan 2.9


Thêm đoạn code sau vào Dockerfile trong thư mục có đường dẫn /ckan/Dockerfile trong repo của bạn

```
RUN pip install -e git+https://github.com/tuancy/ckanext-skt_theme.git@new_theme#egg=ckanext-skt_theme

```

Thêm ```skt_theme``` vào cấu hình ckan.plugins của ckan trong /ckan/Dockerfile.
