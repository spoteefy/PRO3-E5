Project 3 - Ứng dụng học sâu trong tìm kiếm câu hỏi tương đồng
Readme v.13/1/2024
Sinh viên thực hiện: Nguyễn Văn Thọ | 20204694 | IT1-04 K65
GVHD: TS. Trần Văn Đặng, Khoa Khoa học máy tính, Trường CNTT&TT
----------

1. File data/pair-question.jsonl chứa dữ liệu huấn luyện. Chi tiết bộ dữ liệu này được nêu trong Báo cáo Project 3.

2. model/content/intfloat-multi.../14734/ chứa mô hình đã được huấn luyện sẵn E5base+SimCSE-unsupervised
(các thông số huấn luyện được nêu trong báo cáo) 
Để có thể chạy được mô hình này, có thể:
- Upload thư mục này lên HuggingFace
- Dùng lệnh Python để tải mô hình như thực hiện với các mô hình khác từ HuggingFace như intfloat/multilingual-e5-base
hay bert-base-uncased,...

Nếu muốn huấn luyện lại hay thay đổi thông số huấn luyện thì dùng file Code_Project3_20231.ipynb.

3. File Code_Project3_20231.ipynb bao gồm tất cả các lệnh dùng trong dự án này. Để huấn luyện mô hình hay kiểm thử, 
theo dõi các chú thích trong notebook.
Lưu ý:
- Đối với Kaggle, chạy bằng GPU P100 (cần xác thực số điện thoại mới dùng được GPU)
- Đối với Colab, chạy bằng GPU T4. 
Đối với thư viện Gradio, hiện nay chỉ mới hỗ trợ trên Colab, nên đề xuất chạy mô hình này trên Colab.

4. Các file còn lại là file báo cáo (Report_Project3_20231.pdf) và file thuyết trình (Slide_Project3_20231.pptx).