# BÁO CÁO KIỂM THỬ API

## Tên Dự Án: Test Collection of APIs

- **Ngày Kiểm Thử**: 19/6/2025
- **Người Kiểm Thử**: Lê Văn Hiếu

### 1. Mục Tiêu Kiểm Thử
Sử dụng Postman để kiểm thử một API thực tế.

### 2. Môi Trường Kiểm Thử
Postman.

### 3. Phương Pháp Kiểm Thử
Kiểm thử tự động và thủ công trên phần mềm Postman.

### 4. Kịch Bản Kiểm Thử

#### Kịch Bản Kiểm Thử Lần 1
- **Tên Kịch Bản**: Kiểm thử cơ bản của 1 URL
- **Mục Đích**: Test khả năng hoạt động của URL và phần mềm Postman
- **Phương Thức HTTP**: GET
- **URL**: https://jsonplaceholder.typicode.com/
- **Tham Số**: comments?postId=1
- **Kết Quả Mong Đợi**: Gửi yêu cầu thành công
- **Kết Quả Thực Tế**: Đã gửi yêu cầu thành công
- **Trạng Thái**: Thành công
- **Kết Quả Sau Khi Kiểm Thử**:
     ![Image](https://github.com/user-attachments/assets/d4cea423-c58f-41e7-8330-52feefad9262)
**Kết quả kiểm thử chi tiết**:
```json
[
    {
        "postId": 1,
        "id": 1,
        "name": "id labore ex et quam laborum",
        "email": "Eliseo@gardner.biz",
        "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
    },
    {
        "postId": 1,
        "id": 2,
        "name": "quo vero reiciendis velit similique earum",
        "email": "Jayne_Kuhic@sydney.com",
        "body": "est natus enim nihil est dolore omnis voluptatem numquam\net omnis occaecati quod ullam at\nvoluptatem error expedita pariatur\nnihil sint nostrum voluptatem reiciendis et"
    },
    {
        "postId": 1,
        "id": 3,
        "name": "odio adipisci rerum aut animi",
        "email": "Nikita@garfield.biz",
        "body": "quia molestiae reprehenderit quasi aspernatur\naut expedita occaecati aliquam eveniet laudantium\nomnis quibusdam delectus saepe quia accusamus maiores nam est\ncum et ducimus et vero voluptates excepturi deleniti ratione"
    },
    {
        "postId": 1,
        "id": 4,
        "name": "alias odio sit",
        "email": "Lew@alysha.tv",
        "body": "non et atque\noccaecati deserunt quas accusantium unde odit nobis qui voluptatem\nquia voluptas consequuntur itaque dolor\net qui rerum deleniti ut occaecati"
    },
    {
        "postId": 1,
        "id": 5,
        "name": "vero eaque aliquid doloribus et culpa",
        "email": "Hayden@althea.biz",
        "body": "harum non quasi et ratione\ntempore iure ex voluptates in ratione\nharum architecto fugit inventore cupiditate\nvoluptates magni quo et"
    }
]
```
#### Kịch Bản Kiểm Thử Lần 2
- **Tên Kịch Bản**: Kiểm thử cơ bản của 1 URL với một tham số truyền vào
- **Mục Đích**: Test khả năng hoạt động của URL và phần mềm Postman
- **Phương Thức HTTP**: GET
- **URL**: https://random-data-api.com/api/v2/
- **Tham Số**: beerType=light
- **Kết Quả Mong Đợi**: Gửi yêu cầu thành công
- **Kết Quả Thực Tế**: Đã gửi yêu cầu thành công
- **Trạng Thái**: Thành công

**Kết quả kiểm thử chi tiết**:
```json
{
    "id": 4908,
    "uid": "16d508f9-8757-491d-b8c9-4b980932f637",
    "brand": "Leffe",
    "name": "Sapporo Premium",
    "style": "Strong Ale",
    "hop": "Newport",
    "yeast": "1098 - British Ale",
    "malts": "Roasted barley",
    "ibu": "82 IBU",
    "alcohol": "2.1%",
    "blg": "12.8°Blg"
}
```

### 5. Kết Quả Kiểm Thử
- **Số lượng kịch bản đã kiểm thử**: 2
- **Số lần thành công**: 2
- **Số lần thất bại**: 0
- **Tỉ lệ thành công**: 100%
