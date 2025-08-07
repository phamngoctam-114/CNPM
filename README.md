# CNPM
Dự án CNPM
Readme
Dự án CNPM dự án CNPM intern-management-system/
intern-management-system/

├── backend/ # API services (Express/Django/etc.)

│ ├── src/

│ │ ├── controllers/

│ │ ├── models/

│ │ ├── routes/

│ │ ├── services/

│ │ └── utils/

│ ├── .env

│ ├── app.js

│ └── package.json / manage.py

│

├── frontend/ # (Optional) Frontend app (React/Vue/etc.)

│ ├── public/

│ ├── src/

│ │ ├── components/

│ │ ├── pages/

│ │ ├── services/

│ │ └── App.js

│ └── package.json

│

├── diagrams/ # All system design diagrams

│ ├── context-diagram.drawio

│ ├── ims_erd.drawio

│ ├── use-case.drawio

│ └── *.png / *.svg

│

├── docs/ # Technical documentation

│ ├── system-design.md

│ └── api-guide.md

│

├── openapi_spec.yaml # OpenAPI / Swagger spec

├── README.md # Project overview

└── LICENSE # License file (MIT/GPL/etc.)

________________________________________
Mục tiêu
Hệ thống giúp doanh nghiệp quản lý toàn diện thực tập sinh:
•	Quản lý chiến dịch tuyển dụng và phỏng vấn
•	Xây dựng chương trình đào tạo
•	Theo dõi tiến độ và đánh giá năng lực
•	Giao tiếp mentor ↔ intern hiệu quả
________________________________________
Khởi chạy dự án
# 1. Cài đặt thư viện cần thiết
pip install -r requirements.txt

# 2. Chạy ứng dụng Flask
python run.py
