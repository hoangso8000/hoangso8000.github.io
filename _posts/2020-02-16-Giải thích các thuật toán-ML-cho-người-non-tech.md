---
layout: post
title:  "ML theo 1 cách dễ hiểu"
date:   2014-02-16
---

<p class="intro">1 Buổi tối mà mãi không ngủ được bèn mở cái laptop lên định xem cái gì đó cho buồn ngủ thì run rủi thế nào lại đi đọc mấy cái blog để tiếp tục tìm hiểu về AI, ML, DL. Cho những ai chưa hiểu về mấy thuật ngữ trên thì giải thích một cách dễ hiểu thì AI là trí tuệ nhân tạo ML là học máy là một mảng trong đó và trong học máy là học sâu dựa trên thuật toán mạng nơron của học sâu. Trong thời đại hiện nay thì mọi người cứ thần thánh hóa về nào là trí tuệ nhân tạo về học máy  bla bla .... Thật ra mọi người chúng ta chưa hiểu thực sự về nó cứ nghĩ nó là 1 cái gì cao siêu lắm</p>

Nếu bạn suy nghĩ 1 chút thì ta có thể nhận ra cả quá trình dự đoán cho mô hình là 1 cuộc chiến. Ta coi dữ liệu là kẻ thù, hiểu biết của mình cách nén dữ liệu(data mining) và các thuật toán chính là vũ khí
<img src="{{ '/assets/img/army2.jpg' | prepend: site.baseurl }}" alt=""> 

### Có 3 loại thuật toán học máy
*Học có giám sát: bạn đi vào 1 cuộc chiến và không ngừng tiêu diệt bất kì kẻ thù ngáng đường ở đây bao gồm hồi qui tuyến tính(Linear Regression), Logistic Regression, Cây quyết định,..
*Học không giám sát: Đối phương thách thức bạn cho 1 cuộc chiến bây giờ bạn phải quyết định là chiến hay đầu hàng sau khi xem xét lại sức mạnh của mình. Ở đây bao gồm các thuật toán như K-means, apricot 
*Học củng cố: Bạn chiến đấu và khi cuộc chiến bắt đầu thì từng giờ từng phút bạn cần phải xem xét tình thế của mình: Liệu mình có đang thiệt hại nhiều hơn không ? Đối phương đang yếu rút lui? Và từ đó bạn cần quyết định là chiến tiếp hay lui quân

### Giaỉ thích 10 thuật toán học máy cho một người chiến sĩ


### 1. Linear Regression
Linear Regression tức là khi mình chiến đấu thì không có nhìn laị và chỉ nghỉ ngơi khi mình đã tiêu diệt toàn bộ kẻ địch 

### 2. Logistic Regression
Thuật toán này đơn giản là tổng hợp lại các điều kiện ta có và địch có để quyết định xem lui hay tấn công tiếp

### 3. Tree Based Modeling
Thuật toán này bao gồm  Decision Trees, Random Forest. Đơn giản chỉ là ta sẽ tiến hành chia để trị. Chia đối phương ra với chiến thuật nào đó rồi tiêu diệt thôi

### 4. Bayesian Modeling
Thuật toán này dựa trên xác suất có điều kiện như ta xác định xem xác suất ta có thể thắng nếu thời tiết có mưa, hoặc ở các địa hình chiến đấu khác nhau .... và từ những con số đó có thể đưa ra những quyết định hợp lý

### 5. Support Vector Machines

Thuật toán này sẽ cho ta 1 khoảng ranh giới lãnh thổ nơi mà ở đó chúng ta sẽ có lợi. Ví dụ quân ta sẽ thích nghi tốt hơn với thời tiết nóng ẩm 

### 6. kNN (k Nearest Neighbour)
KNN sẽ kiểm tra những kết quả trong quá khứ và đem so sánh với hiện tại, ước lượng hiệu quả của các trận chiến trước để tìm ra khuyết điểm và ưu điểm từ đó chuẩn bị cho trận tiếp theo

### 7. k means 
Đây là thuật toán phân cụm tức là chúng ta sẽ tiến hành tìm kiếm đồng minh với những khu vực có cùng mục đích lý tưởng chiến đấu. Điều đó sẽ giúp lực lượng mạnh hơn bao giờ hết

### 8.  Neural Network and Perceptron
Neural Network dựa trên mạng nơ ron của con người và mỗi node ở đây là 1 người lính. Mỗi người lính sẽ quyết định là chiến đấu với ai. Theo 1 cách tự nhiên thì khi chiến đấu thì người chiến sĩ sẽ thường thích đấu với những kẻ yếu hơn bằng sự quan sát và phân tích của họ để có thể tiêu diệt nhanh hơn. Điều đó sẽ tác động đến chiến thuật của toàn đội

### 9. Ensemble Modeling 
Khi chúng ta có một binh đoàn bao gồm những chiến sĩ có những kĩ năng khác nhau trong chiến đấu như là xạ thủ, kiếm khách, ... cùng chung 1 mục đích là chiến thắng kẻ thù. Tất cả những người này sẽ tập hợp thành 1 đội kinh khủng

### 10. Anomaly Detection
Đây là như kiểu ta sẽ tìm điểm bất thường của đối phương nhờ nội gián 
