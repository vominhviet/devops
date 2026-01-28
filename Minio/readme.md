# Luồng hoạt động user
- Tạo Policy bằng Json [Json_quyền read + write](https://github.com/vominhviet/devops/blob/main/Minio/Json_bucket_policy.txt)
- Tạo Bucket -> gán user và policy vào

# Upload video mc
- **1 Khai báo alias:** `mc alias set local http://localhost:9000 minioadmin minioadmin`
- **2 Liệt kê bucket:** ` mc ls local` or `mc alias ls`
- **3 coppy toàn bộ dữ liệu vào bucket:** `mc cp -r /data/nơi chứ video/ local/tên bucket/thư mục chứa`

# Replication
