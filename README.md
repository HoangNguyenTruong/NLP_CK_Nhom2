# NLP_CK_Nhom2
Đề tài: Phân tích quan điểm bình luận về sản phẩm quần áo trên các sàn thương mại điện tử

Đây là bài báo cáo cuối kì nhóm 2 môn xử lý ngôn ngữ tự nhiên của lớp Khoa học dữ liệu (DS) thuộc Đại học Kinh tế thành phố Hồ Chí Minh (UEH). Đề tài sẽ tiến hành ứng dụng các phương pháp vectorize ngôn ngữ tự nhiên (Bag of word, TFIDF, word indexing, pretrainmodel) và ứng dụng 3 mô hình học máy (logistic regression, random forest, NaiveBayes) với 1 mô hình học sâu (LSTM) để đưa ra phân tích đánh giá. Bên cạnh đó, nhóm cũng sẽ tiến hành phân tích phương pháp vectorize kết hợp với mô hình nào sẽ phù hợp với những comment dài và những comment ngắn. 

Thành viên:

     1. Nguyễn Trương Hoàng

     2. Nguyễn Thành Vinh
     
     3. Lê Quyết
     
     4. Võ Yến Nhi

Nội dung của các đoạn folder, file:

     Folder Data: Lưu trữ tập dữ liệu gốc ban đầu; tập dữ liệu sau khi text preprocessing; tập dữ liệu phục vụ text processing: stopword, teencode
     Folder Vectorize: Lưu trữ kết quả chạy 3 mô hình học máy, 1 mô hình học sâu (LSTM) đối với từng phương pháp vectorize tương ứng với tên file và 1 file để hyperparameter tunning mô hình ML, DL
     TextprocessingEDA: File lưu trữ hàm để tiền xử lý dữ liệu và phân tích khám phá dữ liệu

