# Plastic Pollution Analysis and Prediction

## 1. Giới thiệu

Đồ án phân tích lượng phát thải rác thải nhựa và hiệu quả quản lý chất thải tại các quốc gia trên thế giới.

Dự án thực hiện toàn bộ quy trình từ thu thập dữ liệu, tiền xử lý, Join/Merge nhiều bảng dữ liệu, phân tích khám phá dữ liệu (EDA), xây dựng dashboard tương tác bằng Tableau Public và áp dụng Machine Learning để dự đoán lượng phát thải nhựa cũng như phân loại các khu vực có nguy cơ phát thải cao.

---

## 2. Mục tiêu

Dự án hướng đến các mục tiêu chính:

- Phân tích lượng phát thải nhựa tại cấp quốc gia và đô thị.
- Đánh giá mối quan hệ giữa tỷ lệ tái chế, độ bao phủ thu gom và phát thải nhựa.
- Phân tích sự khác biệt về phát thải giữa các khu vực và nhóm thu nhập.
- Xây dựng Dashboard tương tác bằng Tableau Public.
- Xây dựng mô hình Machine Learning để dự đoán lượng phát thải nhựa.
- Phân loại nguy cơ phát thải cao bằng Logistic Regression.
- Tích hợp kết quả dự đoán Machine Learning vào Tableau.

---

## 3. Nguồn dữ liệu

Dữ liệu được sử dụng từ bộ dữ liệu của Cottom et al. về phát thải rác thải nhựa toàn cầu.

Các bảng dữ liệu chính được lưu trong thư mục:

`data/raw/`

### Lưu ý về dữ liệu SD05

File `SD_05_Cottom_et_al_V1.1.0-G-1223_SPOT_MFA_Outputs_Municipal.xlsx`
được sử dụng trong quá trình xử lý và phân tích dữ liệu ở cấp municipality.

Do kích thước file khoảng 629 MB, vượt giới hạn 100 MB của GitHub,
file này không được lưu trực tiếp trong repository.

**Nguồn dữ liệu:**  
Cottom et al. (2024), *A local-to-global emissions inventory of macroplastic pollution*.

**Dryad Dataset:**  
https://doi.org/10.5061/dryad.8cz8w9gxb

## 4. Dashboard Tableau Public

Dashboard tương tác của đồ án được công bố tại Tableau Public:

https://public.tableau.com/views/Plastic_Pollution_Dashboard_WIP_2026-10-05/18_ML_Top_Prediction_Error?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link