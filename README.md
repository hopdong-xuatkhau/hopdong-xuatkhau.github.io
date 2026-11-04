# Hợp đồng Sài Gòn – Bangkok

Trò chơi lớp học môn **Nghiệp vụ ngoại thương & Logistics** (Nhóm 1). Cả lớp vào vai phòng xuất khẩu của Công ty CP Thực phẩm An Nam, soạn hợp đồng bán xoài sấy dẻo cho chuỗi siêu thị Siam Retail (Bangkok, Thái Lan). Kết thúc trò chơi, hợp đồng còn trống đúng một ô (giá cả) và dẫn thẳng vào phần thuyết trình **Nghệ thuật đàm phán với các nước ASEAN – Thái Lan**.

**Chơi ngay:** https://hopdong-xuatkhau.github.io/

## Cách chơi

1. Ở màn hình đầu, chọn số nhóm trong lớp (mặc định loại Nhóm 1 vì đang thuyết trình), thời gian trả lời và các câu hỏi muốn dùng.
2. Mỗi câu hỏi là một điều khoản của hợp đồng. Nhóm nào giơ tay thì bấm chọn nhóm đó; không ai giơ tay thì bấm **Quay ngẫu nhiên**.
3. Bấm đáp án nhóm đưa ra:
   - **Đúng:** điều khoản được ghi vào hợp đồng (Sales Contract song ngữ Anh – Việt) và container đi thêm một chặng.
   - **Sai:** hiện ra sự cố xảy ra với hợp đồng (kẹt cảng, mất tiền, tranh chấp…), sức khỏe hợp đồng giảm. Có thể mời nhóm khác trả lời hoặc xem đáp án.
4. Hết câu hỏi: màn hình chỉ đóng dấu **HỢP ĐỒNG HỢP LỆ** (sức khỏe từ 50%) hoặc **KHÔNG HỢP LỆ** (dưới 50%), rồi bấm **Bước vào bàn đàm phán** để chuyển sang bài thuyết trình.

Phím tắt: `A`–`D` chọn đáp án · `Q` quay nhóm · `Enter` sang câu tiếp · `F` toàn màn hình.

## Nội dung 6 câu hỏi

| Bước | Điều khoản | Kiến thức |
|---|---|---|
| 1 | Chào hàng | Chào hàng cố định và chào hàng tự do (Chương 2) |
| 2 | Giao hàng | **Incoterms® 2020: FOB Cát Lái** (Chương 1) |
| 3 | Thanh toán | L/C không hủy ngang, trả ngay; so với T/T, D/A, nhờ thu trơn (Chương 3) |
| 4 | Chứng từ | C/O Form D để hưởng thuế 0% theo ATIGA, FDA Thái, VAT 7% |
| 5 | Phản hồi của người mua | Hoàn giá và chấp nhận (Chương 2) |
| 6 | Bàn đàm phán | Ba kiểu đàm phán, dẫn vào bài thuyết trình |

Nguồn: bài giảng Nghiệp vụ ngoại thương (Chương 1–3) và tiểu luận Nhóm 1 “Nghệ thuật đàm phán với Thái Lan”.

## Kỹ thuật

- Một file `index.html` duy nhất, không cần cài đặt, chạy trên mọi trình duyệt.
- Có giao diện sáng/tối, dùng được trên máy chiếu và điện thoại.
- Tự lưu ván đang chơi: lỡ tải lại trang vẫn bấm “Tiếp tục ván đang chơi” được.
- Nền là cảnh cảng container Cát Lái (cần cẩu, tàu, xe container, tàu lai dắt), tự đổi sang cảnh đêm ở giao diện tối.
- Đã chạy thử tự động hơn 500 ván (ngẫu nhiên số nhóm, câu hỏi, đúng/sai, vòng quay) để kiểm tra hợp đồng, kết quả hợp lệ/không hợp lệ và lỗi.
