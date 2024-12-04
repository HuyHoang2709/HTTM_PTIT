# Các bước chạy file

1. Tải dataset từ [Kaggle](https://www.kaggle.com/datasets/jayeshrohansingh/emotion-detection-dataset?resource=download)
2. Giải nén file `archive.zip` vừa tải về và xoá các nhãn ảnh không cần thiết, chỉ giữ lại 4 nhãn: Happy, Angry, Sad, Neutral
3. Đưa folder đã `fer2013` vào folder `dataset`
4. Nén folder `dataset` thành file `dataset.zip`
5. Tải file `dataset.zip` lên Google Drive
6. Truy cập [Google Colab](https://colab.research.google.com/) với tài khoản Google có drive chứa file dataset ở trên
7. Chọn Upload -> chọn file `emotion_detection.ipynb`
8. Chọn Runtime -> Change runtime type -> chọn T4 GPU để tăng tốc độ train
9. Chạy 3 code block đầu file để tải tập dữ liệu trên Colab
10. Chạy các dòng sau như bình thường
