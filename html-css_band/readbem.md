# Bem
Là tiêu chuẩn đặt tên clas khi viết css

## Ý nghĩa:
Viết tắt của Block Elêment Modifỉe
Block: Khối
Element: Thành Phần trong khối
Modifỉer: Bổ sung ý nghĩa cho `Block` hoặc `Element`

## Tại sao phải dùng BEM?
- Mỗi người đặt một kiểu
- Members đặt class trùng nhau, css đè lên nhau

## Cú pháp
- .block
- .block_element

- .block--modifier
- .block__element--modifier

## Tính ứng dụng
- Xây dựng layout website
- Xây dựng thành phần trên website

## Ưu điểm
- Tái sử dụng dễ dàng
- Tính rõ ràng
- Giúp cả team làm việc với nhau dễ dàng
- Tính module, không lo CSS của class này ảnh hưởng đến class khác

## Nhược điểm
- Tến class dài
- Một số người cho là xấu

## Khi nào dùng BEM là phù hợp
- Dự án nhiều memebers
- Dự án lớn, số lượng pàgé nhiều hoặc số lượng các thành phần giao diện

## Thực hành
- Button
    - Enabled: Pointer, hover effect
    - Disable: Arrow, no effect
- Làm message
- Làm một thành phần trên website

## Trường hợp block lồng nhau
- block con là thành phần dùng chùng
- block 