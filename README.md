# Hợp đồng Sài Gòn – Bangkok

Trò chơi lớp học môn **Nghiệp vụ ngoại thương & Logistics** (Nhóm 1). Cả lớp vào vai phòng xuất khẩu của Công ty CP Thực phẩm An Nam, soạn hợp đồng bán xoài sấy dẻo cho chuỗi siêu thị Siam Retail (Bangkok, Thái Lan). Kết thúc trò chơi, hợp đồng còn trống đúng một ô (giá cả) và dẫn thẳng vào phần thuyết trình **Nghệ thuật đàm phán với các nước ASEAN – Thái Lan**.

**Chơi ngay:** https://hopdong-xuatkhau.github.io/

## Cách chơi

1. Ở màn hình đầu, chọn số nhóm trong lớp (mặc định loại Nhóm 1 vì đang thuyết trình), thời gian trả lời và các câu hỏi muốn dùng.
2. Mỗi câu hỏi là một điều khoản của hợp đồng. Nhóm nào giơ tay thì bấm số của nhóm đó ở dải “Nhóm giơ tay” dưới câu hỏi; không ai giơ tay thì bấm nút bánh lái để quay ngẫu nhiên. Cột bên phải dành trọn cho bản hợp đồng để cả lớp cùng theo dõi.
3. Bấm đáp án nhóm đưa ra:
   - **Đúng:** điều khoản được ghi vào hợp đồng (Sales Contract song ngữ Anh – Việt), container đi thêm một chặng trên bản đồ theo dõi. Hiện giải thích chi tiết: vì sao đáp án đúng và từng đáp án còn lại sai ở đâu.
   - **Sai:** hiện ra sự cố xảy ra với hợp đồng (kẹt cảng, mất tiền, tranh chấp…), giải thích vì sao đáp án đó sai và một gợi ý cho nhóm tiếp theo. Có thể mời nhóm khác trả lời hoặc xem đáp án.
4. Hết câu hỏi: màn hình chỉ đóng dấu **HỢP ĐỒNG HỢP LỆ** (mọi điều khoản đều được các nhóm trả lời đúng) hoặc **KHÔNG HỢP LỆ** (có câu phải bấm “Xem đáp án đúng”), rồi bấm **Bước vào bàn đàm phán** để chuyển sang bài thuyết trình.

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

## Bản hợp đồng

Sales Contract song ngữ theo mẫu hợp đồng mua bán hàng hóa quốc tế (Chương 6): phần mở đầu (số, nơi ký, ngày, căn cứ, thông tin hai bên) và 14 điều khoản: Commodity, Quality, Quantity, Shipment, Payment, Price, Packing and marking, Warranty, Insurance, Claim, Force majeure, Penalty, Arbitration, Other terms. Điều khoản Giá được đặt sau Giao hàng và Thanh toán để các ô trống được điền lần lượt từ trên xuống theo thứ tự câu 1 → 6.

Khi đang ở câu nào, điều khoản tương ứng trong hợp đồng được đóng khung đỏ kèm nhãn “Câu N · đang hỏi” và tự cuộn vào giữa khung hợp đồng; trả lời xong khung chuyển xanh “đã điền”.

## Kỹ thuật

- Một file `index.html` duy nhất, không cần cài đặt, chạy trên máy tính, laptop, máy chiếu, máy tính bảng, iPhone và điện thoại Android (cả màn hình ngang).
- Mặc định giao diện sáng (ban ngày) và không bị chế độ tối của trình duyệt tự làm tối. Nút mặt trăng chuyển sang cảnh cảng ban đêm: trăng, sao, cửa sổ tòa nhà sáng đèn.
- Nền là cảnh cảng container Cát Lái: cần cẩu bờ, tàu, bãi container, xe đầu kéo, tàu lai dắt và dãy nhà cao tầng thành phố.
- Tự lưu ván đang chơi: lỡ tải lại trang vẫn bấm “Tiếp tục ván đang chơi” được.
- Đã chạy thử tự động hơn 600 ván (ngẫu nhiên số nhóm, câu hỏi, đúng/sai, vòng quay) để kiểm tra hợp đồng, kết quả hợp lệ/không hợp lệ, bản đồ hành trình và lỗi.
