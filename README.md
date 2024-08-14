# Dự Đoán Giá Nhà

Dự án "Dự đoán Giá Nhà" tập trung vào việc dự đoán giá bất động sản bằng các kỹ thuật học máy. Bằng cách tận dụng các thư viện Python phổ biến như NumPy, Pandas, Scikit-learn (sklearn), Matplotlib, Seaborn và XGBoost, dự án này cung cấp một giải pháp toàn diện cho việc ước lượng giá chính xác.
## Tổng Quan Dự án

Dự án "Dự đoán Giá Nhà" nhằm phát triển một mô hình có thể dự đoán chính xác giá nhà dựa trên nhiều đặc điểm khác nhau. Nhiệm vụ dự đoán này vô cùng quan trọng trong lĩnh vực bất động sản và tài chính, giúp người mua, người bán và nhà đầu tư ra quyết định sáng suốt. Bằng cách sử dụng các thuật toán học máy và một bộ dữ liệu được chọn lọc, dự án này cung cấp một công cụ mạnh mẽ để ước lượng giá nhà.
## Những Điểm Nổi Bật

- **Data Collection and Processing:** Dự án sử dụng tập dữ liệu "California Housing", có thể tải trực tiếp từ thư viện Scikit-learn. Tập dữ liệu này bao gồm các đặc điểm như tuổi nhà, số phòng, dân số và thu nhập trung bình. Sử dụng Pandas, dữ liệu được xử lý và chuyển đổi để đảm bảo phù hợp cho việc phân tích.

- **Data Visualization:** Dự án sử dụng kỹ thuật trực quan hóa dữ liệu để nắm bắt thông tin từ bộ dữ liệu. Matplotlib và Seaborn được sử dụng để tạo ra các hình ảnh như biểu đồ histogram, biểu đồ phân tán và ma trận tương quan. Những hình ảnh này giúp hiểu rõ hơn về mối quan hệ giữa các đặc điểm và hỗ trợ trong việc nhận diện xu hướng và khuôn mẫu.

- **Train-Test Split:** Để đánh giá hiệu suất của mô hình hồi quy, dự án sử dụng kỹ thuật chia dữ liệu thành tập huấn luyện và tập kiểm tra. Dữ liệu được chia thành các tập con huấn luyện và kiểm tra, đảm bảo rằng mô hình được huấn luyện trên một phần của dữ liệu và được đánh giá trên dữ liệu chưa từng nhìn thấy. Điều này cho phép đánh giá chính xác khả năng dự đoán của mô hình.

- **Model Evaluation:** Dự án đánh giá hiệu suất của mô hình hồi quy bằng cách sử dụng các chỉ số đánh giá như sai số bình phương trung bình (MSE) và sai số tuyệt đối trung bình (MAE). Các chỉ số này cung cấp cái nhìn khách quan về độ chính xác của mô hình.

## Kết luận

Dự án "Dự Đoán Giá Nhà" cung cấp một giải pháp thực tiễn để ước lượng giá nhà dựa trên nhiều đặc điểm khác nhau. Bằng cách tận dụng việc thu thập dữ liệu, tiền xử lý, trực quan hóa, mô hình hồi quy và đánh giá mô hình, dự án này mang đến một cách tiếp cận toàn diện để giải quyết tác vụ dự đoán giá cả. Dự án sử dụng tập dữ liệu "California Housing" từ Scikit-learn, đảm bảo nguồn dữ liệu đáng tin cậy và dễ tiếp cận.

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more information.
