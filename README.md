# HaibotLab Releases

## 1. Tải bản phát hành

Chọn gói phù hợp:

```bash
# tar.gz – nhanh, khuyên dùng cho Linux
wget https://github.com/phamduyaaaa/haibotlab-releases/releases/download/haibotlab_gui_v3.1/haibotlab_v3-1.0-Linux-x86_64.tar.gz
```
```bash
# tar.xz – dung lượng nhỏ nhất
wget https://github.com/phamduyaaaa/haibotlab-releases/releases/download/haibotlab_gui_v3.1/haibotlab_v3-1.0-Linux-x86_64.tar.xz
```
```bash
# zip – cross-platform
wget https://github.com/phamduyaaaa/haibotlab-releases/releases/download/haibotlab_gui_v3.1/haibotlab_v3-1.0-Linux-x86_64.zip
```
## 2. Tải file checksum
```bash
wget https://github.com/phamduyaaaa/haibotlab-releases/releases/download/haibotlab_gui_v3.1/SHA256SUMS
```
## 3. Kiểm tra checksum
```bash
sha256sum -c SHA256SUMS
```
## 4. Giải nén gói tương ứng
```bash
tar -xzf haibotlab_v3-1.0-Linux-x86_64.tar.gz
```
```bash
tar -xzf haibotlab_v3-1.0-Linux-x86_64.tar.xz
```
```bash
tar -xzf haibotlab_v3-1.0-Linux-x86_64.zip
```
## 5. Vào thư mục
```bash
cd haibotlab_v3-1.0-Linux-x86_64
```
## 6. Phân quyền chạy
```bash
chmod +x haibotlab_v3
```
# Chạy
```bash
./haibotlab_v3
```
