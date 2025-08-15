# Graduation Project — Customer Churn Analysis & Prediction



## 1) Goals of the project 🎯

Business Goal:
Giảm tỷ lệ khách hàng rời bỏ (churn) và duy trì doanh thu ổn định bằng cách:

Xác định các yếu tố quan trọng tác động đến hành vi rời bỏ.

Dự đoán khả năng rời bỏ của từng khách hàng hiện tại hoặc mới.

Đưa ra giải pháp giữ chân khách hàng hiệu quả dựa trên phân tích dữ liệu.

Questions to answer:

Mô hình nào giải thích tốt nhất các yếu tố dẫn đến churn?

Yếu tố nào tác động mạnh nhất đến khả năng rời bỏ? Có bằng chứng thống kê?

Từ dữ liệu, có thể rút ra insight gì cho chiến lược giữ chân khách hàng?

Ngưỡng xác suất dự đoán nào giúp mô hình phát hiện được nhiều nhất khách hàng có khả năng rời bỏ (churn)?

2) Data sources 🗂️

Name: E-commerce Customer Churn Analysis & Prediction

Source: Kaggle Dataset

Orginal link: https://www.kaggle.com/code/rishavwalde/e-commerce-customer-churn-analysis-and-prediction/notebook#Data-Exploration-and-Visualization

Description:
Dữ liệu chứa hồ sơ khách hàng và các đặc điểm liên quan đến hành vi rời bỏ, bao gồm: thời gian gắn bó (Tenure), điểm hài lòng (SatisfactionScore), khiếu nại (Complain), khoảng cách kho-hàng (WarehouseToHome), số thiết bị, tình trạng hôn nhân, phương thức thanh toán ưa thích, v.v.

3) Data overview 🔍

Dataset size: 5630 hàng × 20 cột

<img width="861" height="852" alt="image" src="https://github.com/user-attachments/assets/45ea4bbf-0346-470d-8e54-1601bb65ad62" />
<img width="860" height="127" alt="image" src="https://github.com/user-attachments/assets/8b12af58-3790-4c71-97ab-549407893cad" />

4) Analytical tools used 📚

Language: Python

Data Analysis: pandas, numpy

Visualization: matplotlib, seaborn

Modeling: statsmodels, scikit-learn (Logistic Regression)

Environment: Google Colab

5) Model 📊

Model used: Logistic Regression

Train/Test split: 70/30

Threshold for churn classification: 0.5

Evaluation metrics: F1-score, Precision, Recall 

6) Forcasting New Customer

Xây dựng một mô hình dự đoán khả năng khách hàng mới sẽ rời bỏ (churn) dựa trên hồ sơ và hành vi ban đầu, từ đó xác định các yếu tố quan trọng nhất dẫn đến churn.

7) Summary and Suggestions

Insight chính:

Giai đoạn “golden stage” 0–3 tháng cần ưu tiên chăm sóc đặc biệt.

Khiếu nại là tín hiệu cảnh báo churn mạnh nhất.

Điểm hài lòng thấp liên quan chặt chẽ với rời bỏ.

Hành động đề xuất:

Giải quyết khiếu nại nhanh chóng và chủ động.

Chương trình onboarding và khuyến mãi chào mừng cho khách hàng mới.

Cải thiện trải nghiệm đặt hàng qua điện thoại hoặc chuyển sang kênh online.

Tăng cường hỗ trợ giao hàng cho City Tier 3 và các khu vực xa kho.

















