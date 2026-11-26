# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 07
- **Họ tên:** Vũ Quốc Linh
- **Lớp:** CNTT1
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé vào cổng ra JSON

**KET QUA AI**

```text
[
  {
    "loai_ve": null,
    "ngay_choi": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_tu": "nho",
    "ghi_chu": null
  },
  {
    "loai_ve": "VECN",
    "ngay_choi": "2027-01-03",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_tu": null,
    "ghi_chu": "Một người đang bó bột tay"
  },
  {
    "loai_ve": "VEVIP",
    "ngay_choi": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_tu": "lon",
    "ghi_chu": "Một bạn đi xe lăn"
  }
]
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e502-3c84-83ec-8f34-4d76fd2ad881

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
BÁO GIÁ VÉ ĐOÀN TRƯỜNG

1. Tiền vé người lớn

8 người lớn × 250.000 = 2.000.000 đồng

2. Tiền vé trẻ em
- 4 trẻ em từ 1 m đến 1,4 m: 250.000 × 60% = 150.000 đồng/vé.
- 4 × 150.000 = 600.000 đồng
- 2 bé dưới 1 m: miễn phí = 0 đồng
3. Tổng tiền vé

2.000.000 + 600.000 + 0 = 2.600.000 đồng

4. Giảm giá đoàn

Đoàn có 8 người lớn nên được giảm 10%.

2.600.000 × 10% = 260.000 đồng

5. Phụ thu thuê áo phao

6 × 40.000 = 240.000 đồng

6. Tổng tiền thanh toán

(2.600.000 - 260.000) + 240.000

= 2.340.000 + 240.000

= 2.580.000 đồng
Tổng thanh toán
[RESULT: 2580000 đồng]
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e543-33cc-83ec-b132-94e349f2cb64

### b) Kiểm tra kết quả AI

Câu trả lời của AI là đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "dong_khu_choi",
  "so_khach": 4,
  "so_khu_bi_dong": 2,
  "tom_tat": "Hai khu vui chơi đóng cả ngày không thông báo trước, ảnh hưởng 4 khách."
}
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e57c-a238-83ec-903a-a102592765ee

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
|---|---:|---|---|
| Đúng thông tin (50%) | 0/5 | Giá vé 150.000 đồng sai với giá chuẩn 180.000 đồng. Chính sách hoàn tiền mặt 100% cũng sai quy định công ty. | Sửa giá vé thành 180.000 đồng. Thông báo đúng chính sách: dưới 2 giờ được tặng 1 vé cùng loại sử dụng trong 30 ngày; từ 2 giờ trở lên không được bù. |
| Đầy đủ (30%) | 0,5/3 | Có đề cập giá vé và chính sách thời tiết nhưng chưa giải thích đầy đủ điều kiện áp dụng. Chưa hỏi khách ngày chơi và số lượng vé. | Trả lời đầy đủ hai câu hỏi và mời khách cung cấp ngày chơi, số lượng vé để đặt vé. |
| Giọng điệu (20%) | 1/2 | Có sử dụng từ lịch sự như "ạ", "chị" nhưng các cụm "mát rượi luôn", "ới em nhé" chưa chuyên nghiệp. | Sử dụng ngôn ngữ lịch sự, chuyên nghiệp và rõ ràng hơn. |
| **Tổng điểm** | **1,5/10** | **Chưa đáp ứng yêu cầu tư vấn của công ty.** | **Cần chỉnh sửa nội dung trước khi gửi khách hàng.** |
```

**Link trò chuyện:** https://chatgpt.com/share/6b07e5e7-6ad8-83ec-9339-dabf5c840c4f
