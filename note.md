NHỚ:
    mỗi ngôn ngữ đều có 1 nơi lưu trữ cái package (kiểu đồ chơi cài vào cho ngôn ngữ đó)
    ví dụ: 
        ở ``NodeJS``: 
            thì nó lưu trữ ở file ```.json``, cái dependencies là nơi liệt kê các đồ chơi
            khi clone về thì nó không tải kèm đồ chơi mà chỉ tải mỗi source src và file ```.json``
            khi này chưa chạy được vì nó còn thiếu đồ chơi
            muốn tải đồ chơi về thì phải dùng đúng lệnh ở mỗi nơi lưu
            ở đây các đồ chơi lưu ở ``npm`` thì dùng lệnh ``npm install``
            nếu nó lưu ở ``yarn`` thì dùng ```yarn add```

        ở vai trò là devops thì mày nên tìm hiểu về tất cả các thư viện build của từng ngôn ngữ phổ biến
