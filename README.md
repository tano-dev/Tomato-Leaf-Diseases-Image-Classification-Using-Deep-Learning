# Tomato-Leaf-Diseases-Image-Classification-Using-Deep-Learning
---
## 🍅 Bài Toán: Nhận Dạng và Phân Loại Bệnh Trên Lá Cây Cà Chua

Sử dụng các phương pháp **Xử lý Ảnh** và mô hình **Deep Learning** để tự động nhận diện và phân loại các bệnh trên lá cây cà chua.

---

### 📥 INPUT (Dữ Liệu Đầu Vào)

| Thuộc Tính | Mô Tả Chi Tiết |
| :--- | :--- |
| **Dữ Liệu** | Hình ảnh của lá cà chua. |
| **Định Dạng** | .jpg, .png. |
| **Kích Thước Xử Lý** | Ảnh được **resize về $128 \times 128$ pixels**. *(Mục đích: Tối ưu tốc độ tính toán, vẫn giữ các đặc trưng quan trọng).* |
| **Dataset (Bộ Dữ Liệu)** | Hình ảnh từ bộ dữ liệu **PlantVillage (Tomato)**. |
| **Số Lượng Lớp** | **6 Lớp** (6 loại lá khác nhau) - *(Đây là bài toán phân loại đa lớp/Multi-Class Classification).* |

#### 🌿 Các Lớp Phân Loại (6 Loại Lá)

| STT | Tên Bệnh (Tiếng Anh) | Tên Bệnh (Tiếng Việt) |
| :--- | :--- | :--- |
| 1 | Bacterial Spot | Đốm vi khuẩn |
| 2 | Early Blight | Bệnh đốm sớm |
| 3 | Healthy | Lá khỏe mạnh |
| 4 | Septorial Leaf Spot | Đốm lá Septoria |
| 5 | Leaf Mold | Nấm mốc lá |
| 6 | Yellow Leaf Curl Virus | Virus xoăn vàng lá |

---

### ⚙️ Phương Pháp/Mô Hình Đề Xuất

* **Lĩnh vực chính:** Computer Vision, Deep Learning.
* **Mô hình phổ biến:** Convolutional Neural Networks (CNN) như **VGG**, **ResNet**, **MobileNet**, hoặc một kiến trúc CNN tùy chỉnh *(Custom CNN Architecture)*. 

[Image of Convolutional Neural Network architecture]

* **Kỹ thuật Xử lý Ảnh:** Tiền xử lý (Preprocessing) bao gồm **Resize**, **Chuẩn hóa (Normalization)**, và **Tăng cường dữ liệu (Data Augmentation)** để cải thiện hiệu suất mô hình.

---

### 📤 OUTPUT (Kết Quả Đầu Ra)

* **Phân loại bệnh:** Mô hình Deep Learning sẽ đưa ra dự đoán về loại lá cà chua, chỉ rõ:
    * Lá thuộc loại bệnh nào trong 5 loại bệnh trên.
    * Hoặc Lá **khỏe mạnh (Healthy)**.

---

### 📈 Đánh Giá (Metrics)

* Các chỉ số quan trọng để đánh giá hiệu suất mô hình:
    * **Accuracy** (Độ chính xác tổng thể).
    * **Precision, Recall, F1-Score** (cho từng lớp và trung bình).
    * **Confusion Matrix** (Ma trận nhầm lẫn).

---

Bạn có muốn tôi đi sâu hơn vào **kiến trúc mô hình CNN** nào sẽ phù hợp nhất cho bài toán này, hay muốn tìm hiểu về các bước **tiền xử lý ảnh** cụ thể?
