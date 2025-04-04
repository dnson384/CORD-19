# Phân tích Xu hướng COVID-19 từ Dataset CORD-19


## Giới thiệu
Bài toán này nhằm mục đích phân tích xu hướng của các bài báo về COVID-19 được thể hiện trong Dataset CORD-19 trên Kaggle. Nhóm mình tập trung vào việc theo dõi tần suất xuất hiện của các từ khóa liên quan đến đại dịch, các biến thể virus, vắc-xin, số ca bệnh và tử vong theo thời gian. Mục tiêu chính là đối chiếu những xu hướng này với diễn biến thực tế của dịch bệnh để xem liệu các bài báo có phản ánh đúng tình hình thực tế tại các thời điểm khác nhau hay không.


## Phương pháp
Sử dụng Jupyter Notebook để xử lý và phân tích dữ liệu từ Dataset CORD-19. Quá trình phân tích tập trung vào việc đếm tần suất xuất hiện của các từ khóa cụ thể trong các bài báo theo từng tháng của những năm khác nhau từ cuối 2019 đến khi hết 2022. Các từ khóa được theo dõi bao gồm:
* Thuật ngữ liên quan đến COVID-19: "relatate\_covid", "relatate\_pandemic", "relatate\_infection".
* Thuật ngữ liên quan đến diễn biến dịch bệnh: "relate\_case", "relate\_death".
* Thuật ngữ liên quan đến biện pháp đối phó: "relate\_vaccine".
* Tên của các biến thể virus: "alpha", "beta", "gamma", "delta", "omicron", "epsilon", "zeta", "eta", "theta", "iota", "kappa", "lambda", "mu".


## Kết quả và Mục tiêu theo Biểu đồ
1.  **Số lượng bài báo về COVID-19 theo năm:** Biểu đồ này cho thấy sự tăng trưởng đáng kể trong số lượng bài báo về COVID-19 từ năm 2019 (trước đại dịch) đến năm 2020, đạt đỉnh vào năm 2021 và sau đó giảm vào năm 2022. Mục tiêu là cung cấp cái nhìn tổng quan về sự quan tâm của cộng đồng theo từng năm và so sánh với các giai đoạn chính của đại dịch.
2.  **Tần suất xuất hiện của các từ khoá về bài báo COVID:** Biểu đồ này so sánh tổng số lần xuất hiện của các thuật ngữ chung ("relatate\_covid", "relatate\_pandemic", "relatate\_infection") trong toàn bộ dataset. Mục tiêu là cung cấp một cái nhìn tổng quan về mức độ bao phủ của dataset đối với các chủ đề cốt lõi của đại dịch.
3.  **Xu hướng từ khoá về các bài báo theo tháng qua các năm:** Biểu đồ này theo dõi tần suất xuất hiện của các thuật ngữ chung ("relatate\_covid", "relatate\_pandemic", "relatate\_infection") theo thời gian. Mục tiêu là xem xét xu hướng tổng thể của các bài báo liên quan đến COVID-19, đại dịch và sự lây nhiễm, từ đó so sánh với các giai đoạn chính của đại dịch.
4.  **Xu hướng từ khoá theo tháng qua các năm:** Biểu đồ này theo dõi tần suất xuất hiện của các từ khóa liên quan đến diễn biến của dịch bệnh và biện pháp đối phó ("relate\_case", "relate\_death", "relate\_vaccine", "relate\_variant") theo từng thán. Mục tiêu là hiểu được sự thay đổi về sự quan tâm về diễn biến dịch bệnh đồng thời nghiên cứu các vắc-xin để đối phó với dịch bệnh và các biến thể khi đại dịch tiến triển.
5.  **Tần suất xuất hiện của các từ khóa về biến chủng COVID (Tổng quan):** Biểu đồ này so sánh tổng số lần xuất hiện của các từ khóa liên quan đến các biến chủng COVID khác nhau trong toàn bộ dataset. Mục tiêu là xác định biến chủng nào được nghiên cứu và nhắc đến nhiều nhất, phản ánh có thể mức độ quan tâm hoặc tác động của chúng.
6.  **Xu hướng từ khóa về biến thể covid theo tháng qua các năm:** Biểu đồ này theo dõi tần suất xuất hiện của từng từ khóa biến thể COVID theo từng tháng. Mục tiêu là xác định thời điểm xuất hiện, giai đoạn phổ biến và sự suy giảm đối với từng biến thể, từ đó so sánh với thời điểm các biến thể này lây lan mạnh mẽ trong thực tế.


## Kết luận
Thông qua việc phân tích các biểu đồ này, nhóm mình mong muốn đối chiếu được sự tương quan giữa xu hướng bài báo và nghiên cứu về COVID-19 trong dataset CORD-19 với diễn biến thực tế của đại dịch. Điều này giúp đánh giá mức độ phản ánh sự quan tâm của cộng đồng về vấn đế này đồng thời cho tính kịp thời của các nghiên cứu khoa học trong việc ứng phó với các diễn biến của đại dịch.