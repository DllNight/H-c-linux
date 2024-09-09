# sed (Stream EDitor)
Thay thế văn bản
Xóa dòng
Chèn dòng
Cắt và dán
Tìm kiếm và thay thế
Cấu trúc cơ bản của lệnh sed:
```
sed 'tác vụ' tệp_đầu_vào
```
Ví dụ:
Thay thế tất cả các từ "old" bằng "new" trong tệp file.txt:
```
sed 's/old/new/g' file.txt
```
tác vụ: Là một hoặc nhiều lệnh sed được đặt trong dấu ngoặc đơn.
tệp_đầu_vào: Tệp văn bản mà bạn muốn xử lý.
#### Các lệnh sed thường dùng:
s/pattern/replacement/g: Tìm kiếm và thay thế tất cả các lần xuất hiện của pattern bằng replacement.
d: Xóa dòng hiện tại.
p: In dòng hiện tại.
a\text: Chèn text sau dòng hiện tại.
i\text: Chèn text trước dòng hiện tại.