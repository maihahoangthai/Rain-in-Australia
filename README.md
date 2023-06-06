# Rain in Australia
Tags: Nhập môn học máy, bài toán phân loại, classification, dự đoán thời tiết.
<br />
**Tên bài toán**: *Rain in Australia (Mưa ở nước Úc)*
<br />
**Nguồn**: ["Rain in Australia" trên Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
<br />
**Code này có tham khảo Notebook**: [Rain Prediction | Analysis with 93.02% accuracy](https://www.kaggle.com/code/ziadshamndy/rain-prediction-analysis-with-93-02-accuracy/notebook)
<br />
**Mô tả bài toán**: Huấn luyện mô hình phân loại (classification model) để từ dữ liệu cho sẵn, hãy dự đoán xem ngày mai có mưa tại nước Úc hay không?
<br />
**Mô tả Dataset cho sẵn**: Tệp dữ liệu 'weatherAUS.csv' có chứa dữ liệu quan trắc thời tiết trong khoảng 10 năm từ nhiều địa điểm trên khắp nước Úc. Cột 'RainTomorrow' của tệp dữ liệu, tức ngày mai có mưa hay không, là mục tiêu mà mô hình cần dự đoán được kết quả. Cột RainTomorrow có 2 class là 'Yes' hoặc 'No'. Theo quan sát, RainTomorrow sẽ là Yes nếu ngày mai đó có nhiều hơn 1mm nước mưa.
<br />
Ta có 23 cột thuộc tính với các ý nghĩa như sau:
<br />
- 0-Date: Ngày thực hiện quan sát.
- 1-Location: Tên của địa điểm đặt trạm khí tượng.
- 2-MinTemp: Nhiệt độ thấp nhất trong ngày (tính bằng độ c).
- 3-MaxTemp: Nhiệt độ cao nhất trong ngày (tính bằng độ c).
- 4-Rainfall: Lượng mưa đo được trong ngày (tính bằng mm).
- 5-Evaporation: Độ bóc hơi (tính bằng mm).
- 6-Sunshine: Số giờ nắng sáng trong ngày.
- 7-WindGustDir: Hướng gió giật mạnh nhất trong ngày.
- 8-WindGustSpeed: Tốc độ của gió giật mạnh nhất (tính bằng km/giờ).
- 9-WindDir9am: Hướng gió lúc 9 giờ sáng.
- 10-WindDir3pm: Hướng gió lúc 3 giờ chiều.
- 11-WindSpeed9am: Tốc độ của gió lúc 9 giờ sáng.
- 12-WindSpeed3pm: Tốc độ của gió lúc 3 giờ chiều.
- 13-Humidity9am: Độ ẩm lúc 9 giờ sáng (tính bằng %).
- 14-Humidity3pm: Độ ẩm lúc 3 giờ chiều (tính bằng %).
- 15-Pressure9am: Áp suất khí quyển lúc 9 giờ sáng.
- 16-Pressure3pm: Áp suất khí quyển lúc 3 giờ chiều.
- 17-Cloud9am: Độ phủ mây lúc 9 giờ sáng.
- 18-Cloud3pm: Độ phủ mây lúc 3 giờ chiều.
- 19-Temp9am: Nhiệt độ lúc 9 giờ sáng;
- 20-Temp3pm: Nhiệt độ lúc 3 giờ chiều.
- 21-RainToday: Ngày hôm nay có mưa không (Yes hoặc No).
- 22-RainTomorrow: Ngày mai có mưa không.
<br />
