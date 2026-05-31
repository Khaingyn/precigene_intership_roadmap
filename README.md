# LỘ TRÌNH HỌC TIN SINH HỌC
*Lộ trình học tin sinh học dành cho sinh viên thực tập tại Công ty PrecisionGene*

# 1. KIẾN THỨC CƠ BẢN
Các bạn sinh viên cần phải nắm rõ được những kiến thức cơ bản nền tảng thì mới có thể đi sâu vào được bất kỳ mảng chuyên môn nào trong tin sinh học (Metagenomics, Genomics, Transcriptomics, v.v.), bao gồm:

## 1.1. Các công cụ và ngôn ngữ nền tảng

* **GitHub:** Đây giống như là một "mạng xã hội" – nhưng thay vì để đăng hình ảnh, video như Facebook, Zalo thì ở đây là nơi cộng đồng trên toàn thế giới đăng tải các công cụ phần mềm mà họ tạo ra, bao gồm cả các công cụ sử dụng trong tin sinh học. Ngoài ra, GitHub còn được dùng để đăng các tài liệu học tập liên quan tới tin sinh học nói riêng cũng như công nghệ thông tin, khoa học máy tính nói chung.
* **Linux và Terminal:** Làm quen với môi trường Linux và sử dụng các câu lệnh (Command Line) để thao tác trực tiếp với hệ thống. Đây là kỹ năng "nhập môn" bắt buộc để vận hành các công cụ tin sinh.
* **Bash script:** Cách viết file chứa tổ hợp các câu lệnh để có thể tự động hóa quy trình và tái sử dụng mã nguồn trong các trường hợp tương tự trong môi trường Linux.
* **Ngôn ngữ lập trình R:** Có thể các bạn đã hoặc sẽ được học ở trường các phần mềm phân tích thống kê như SPSS, Stata, Minitab. Tuy nhiên, đây là những phần mềm tính phí để có thể sử dụng được một cách hợp pháp, và quan trọng hơn là chúng không được ưa chuộng trong tin sinh học vì không thể cung cấp trọn vẹn **khả năng tái lập phân tích (Reproducibility)**. Các thao tác phân tích bằng cách "click chuột" thủ công rất bất tiện khi cần mô tả lại quy trình trong các nghiên cứu khoa học.
    * Ngôn ngữ lập trình R giải quyết được những vấn đề này: nó hoàn toàn miễn phí, các thao tác phân tích là những dòng lệnh R được biên tập gọn gàng trong các file `.R`. Chỉ cần chạy file này là có thể tái lập được các phân tích đã thực hiện một cách dễ dàng và tiện lợi. R được đông đảo cộng đồng thế giới xây dựng và tạo nên các thư viện (tools) mạnh mẽ, đa dạng cho phân tích thống kê và trực quan hóa dữ liệu (vẽ các đồ thị chất lượng cao).

> **Lưu ý về Python:** Ngoài ra còn có ngôn ngữ lập trình Python, cũng có thể được sử dụng trong nhiều trường hợp để thay thế Bash script hoặc R; Python đặc biệt mạnh trong Machine Learning (Học máy), Deep Learning và AI. Tuy nhiên, Linux + Bash script + R là "kiềng ba chân" quan trọng nhất trong kiến thức cơ bản, nên Python sẽ không được ưu tiên trong lộ trình này vì chưa thực sự cần thiết lúc mới bắt đầu. Sau này khi các bạn đã nắm vững 3 công cụ trên, việc tự học thêm Python sẽ trở nên rất dễ dàng với nguồn tài liệu phong phú trên internet.

## 1.2. Tài liệu học tập và thực hành
Các tài liệu sau đây sử dụng từ khoá học MGMA 2024 được thầy Lưu Phúc Lợi tổ chức vào 2024, và các nguồn khác trên mạng

* **Khóa học MGMA 2024 (Online):** Khóa học hướng dẫn về Linux, Bash script và phân tích bộ gen vi khuẩn.
    * **Youtube Playlist:** [Xem tại đây](https://youtube.com/playlist?list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&si=tVECKslizscj9on7)
    * **Tài liệu & Slide (GitHub):** [Truy cập tại đây](https://github.com/UeenHuynh/MGMA_2024)

Nội dung chia ra cho dễ theo dõi:
### Github
- https://www.youtube.com/watch?v=wpIN9kkU7fk&list=PLyxSzL3F7485Xgn7novgNxnou8QU6i485&index=17
- https://www.youtube.com/watch?v=xfFMCtoNDoU
- https://www.youtube.com/watch?v=8CmZKWWpCm0&list=PLyxSzL3F7485Xgn7novgNxnou8QU6i485&index=18
- https://www.youtube.com/watch?v=4FjgUp0zgcM&list=PLyxSzL3F7485Xgn7novgNxnou8QU6i485&index=2 (học sau linux và bash script)
- https://www.youtube.com/watch?v=N_tabayXkdI&list=PLyxSzL3F7485Xgn7novgNxnou8QU6i485&index=19 (học sau linux và bash script)
- https://www.youtube.com/watch?v=q6AxUo-xnx4&list=PLyxSzL3F7485Xgn7novgNxnou8QU6i485&index=20 (học sau linux và bash script)
### Dòng lệnh linux
- https://www.youtube.com/watch?v=5mYu5BOCvKc&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=2
- Google Colab (một phương án tạm thời để có môi trường linux nhanh chóng để thực hành lệnh linux và ngôn ngữ lập trình): https://www.youtube.com/watch?v=O11h2ockwdA&list=PLXtgXP89Tyn-iYKR7_ShHyQEQN3CTt6AW&index=9
- https://www.youtube.com/watch?v=NHq5sqyhybM&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=3
- https://www.youtube.com/watch?v=wBV9j147arU&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=7
- https://www.youtube.com/watch?v=Y0C9AyUu8EE&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=8
- https://www.youtube.com/watch?v=114oATBzX-I&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=15
### Bash script
- https://www.youtube.com/watch?v=bIMtUtNmBW4&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=9
- https://www.youtube.com/watch?v=3r83hXh9qL8&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=12
- vscode: https://www.youtube.com/watch?v=1IU7-67iYbM&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=20
### R
- (Hướng dẫn cài đặt R và R Studio | Window | TS.BS.Vũ Duy Kiên)[https://www.youtube.com/watch?v=ngpB_00Jiyk]
- (Hướng dẫn cài R và R Studio cho máy MAC | TS.BS.Vũ Duy Kiên)[https://www.youtube.com/watch?v=2Xb74YKjPbA]
- https://www.youtube.com/watch?v=5iKr0TWv5xE&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=19
- https://www.youtube.com/watch?v=8GTNqj6YY2o&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=25
- https://www.youtube.com/watch?v=6_4-byxNhB4&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=39
- https://www.youtube.com/watch?v=tig4mchm-bw&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=40
- https://www.youtube.com/watch?v=zcc4s65BKP4&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=41
- https://www.youtube.com/watch?v=1sMDR2NlQtw&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=42
- https://www.youtube.com/watch?v=DZOkXKBbfik&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=65
- https://www.youtube.com/watch?v=K8W1XQr0F8E&list=PLXtgXP89Tyn-cldf3rwqsCh5nR031OD-s&index=66
### R web-book:
- https://r4ds.hadley.nz/ (tiếng Việt: https://vn.r4ds.hadley.nz/)
- https://r-graphics.org/index.html
- https://ggplot2-book.org/
- https://rkabacoff.github.io/datavis/
- https://clauswilke.com/dataviz/
# 2. Phân tích toàn bộ bộ gene (whole genome sequencing - WGS)

