## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
{
"ma_goi": "SVT",
"ngay_su_kien": "2026-12-20",
"nguoi_lon": 2,
"tre_em": 1,
"loai_ve": "thuong",
"ghi_chu": null
},
{
"ma_goi": "FZ",
"ngay_su_kien": "2027-01-05",
"nguoi_lon": 3,
"tre_em": 0,
"loai_ve": "thuong",
"ghi_chu": "hỗ trợ xe lăn"
},
{
"ma_goi": "VIP",
"ngay_su_kien": null,
"nguoi_lon": 4,
"tre_em": 0,
"loai_ve": "vip",
"ghi_chu": "hỗ trợ tìm chỗ"
}
]
```

**Link trò chuyện:** https://share.gemini.google/gk8oCFVnlvA8

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
1. Chuẩn hóa dữ liệu
Gói dịch vụ: SVT (1.200.000 đồng/người lớn)

Số lượng người lớn: 5 người (đủ điều kiện giảm 5%)

Trẻ em từ 5 - 11 tuổi: 2 bé (8 tuổi và 10 tuổi)

Trẻ em dưới 5 tuổi: 1 bé (3 tuổi – miễn phí)

Phụ thu: 1 người chọn khu ghế ưu tiên
2. Suy luận từng bước
Tiền người lớn: $5 \times 1.200.000 = 6.000.000 \text{ đồng}$
Tiền trẻ em: $2 \times (1.200.000 \times 70\%) = 1.680.000 \text{ đồng}$
Tiền vé (trước giảm): $6.000.000 + 1.680.000 = 7.680.000 \text{ đồng}$
Giảm giá nhóm (5%): $7.680.000 \times 5\% = 384.000 \text{ đồng}$ $\rightarrow$ Tiền vé sau giảm: $7.296.000 \text{ đồng}$
Phụ thu: $1 \times 300.000 = 300.000 \text{ đồng}$
Tổng tiền: $7.296.000 + 300.000 = 7.596.000 \text{ đồng}$
[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:** https://share.gemini.google/8KyK1GMmuQfM

### b) Kiểm tra kết quả AI



## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
[
  {
    "loai_su_co": "sai_khu_vuc",
    "sai_khu_vuc": true,
    "so_khach": 2,
    "so_hiep_bi_anh_huong": 2
  }
]
```

**Link trò chuyện:** https://chatgpt.com/share/6afd6942-36d8-83ec-b777-90d0e6f630e9
