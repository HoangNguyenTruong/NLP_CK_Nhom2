# NLP_CK_Nhom2
Đề tài: Phân tích quan điểm bình luận về sản phẩm quần áo trên các sàn thương mại điện tử

Đây là bài báo cáo cuối kì nhóm 2 môn xử lý ngôn ngữ tự nhiên của lớp Khoa học dữ liệu (DS) thuộc Đại học Kinh tế thành phố Hồ Chí Minh (UEH). Đề tài sẽ tiến hành ứng dụng các phương pháp vectorize ngôn ngữ tự nhiên (Frequency Based, TFIDF, word indexing, pretrainmodel) và ứng dụng 3 mô hình học máy (logistic regression, random forest, NaiveBayes) với 1 mô hình học sâu (LSTM) để đưa ra phân tích đánh giá. Bên cạnh đó, nhóm cũng sẽ tiến hành phân tích phương pháp vectorize kết hợp với mô hình nào sẽ phù hợp với những comment dài và những comment ngắn. 

Thành viên:

     1. Nguyễn Trương Hoàng

     2. Nguyễn Thành Vinh
     
     3. Lê Quyết
     
     4. Võ Yến Nhi

Nội dung của các đoạn folder, file:

* Folder Data: Lưu trữ tập dữ liệu gốc; tập dữ liệu sau khi text preprocessing; tập dữ liệu phục vụ text processing <br>
train_category_split_vie, train_sentiment_vie, train_split_sentiment_vie: tập dữ liệu gốc <br>
preprocessed_data, preprocessed_data1: tập dữ liệu đã qua bước text preprocessing <br>
stopword, teencode: tập dữ liệu phục vụ text processing <br>
* Folder Vectorize: Lưu trữ kết quả chạy 3 mô hình học máy, 1 mô hình học sâu (LSTM) đối với từng phương pháp vectorize tương ứng với tên file và 1 file để hyperparameter tunning mô hình ML, DL <br>
FrequentBased: Lưu trữ 3 mô hình ML, 1 mô hình DL đối với phương pháp Frequency Based <br>
TFIDF: Lưu trữ 3 mô hình ML, 1 mô hình DL đối với phương pháp TFIDF <br>
WordIndex: Lưu trữ 3 mô hình ML, 1 mô hình DL đối với phương pháp WordIndexing <br>
PreTraiModel: Lưu trữ 3 mô hình ML, 1 mô hình DL đối với phương pháp ProBert <br>
MLTunning: Điều chỉnh các siêu tham số của 3 mô hình ML <br>
CATEGORY: Sử dụng Frequency Based và RandomForest đề tạo mô hình cho việc dự đoán chủ đề bình luận <br>
UNG_DUNG: Ứng dụng vào thực tế mô hình tốt nhất được chọn trong các mô hình được train để dùng cho tập test <br>
* Folder Model: Lưu trữ mô hình tốt nhất để ứng dụng vào thực thế <br>
* PreprocessingEDA: File lưu trữ hàm để tiền xử lý dữ liệu và phân tích khám phá dữ liệu <br>

