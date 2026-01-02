# 🎄 Grand Luxury Tree

[![Contributors](https://img.shields.io/github/contributors/electronicminer/gesture-Christmas_tree-3d_with_photo?color=dark-green)](https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors)

Xin chào! Đây là một dự án nhỏ được viết để chào mừng Giáng sinh. ✨

Ban đầu chỉ định vẽ một cây thông Noel 3D bình thường, nhưng cảm thấy chưa đủ "cool", nên đã thêm **nhận diện cử chỉ** và **hiệu ứng hạt**. Giờ đây bạn có thể điều khiển cây thông "từ xa" qua camera, và còn có thể treo những bức ảnh yêu thích lên đó.

Dù chỉ có vài trăm dòng code, nhưng hiệu ứng hình ảnh cực kỳ ấn tượng (đặc biệt trên màn hình lớn).

Nhấn vào link bên dưới để truy cập trực tiếp: Hỗ trợ đa nền tảng
https://electronicminer.github.io/gesture-Christmas_tree-3d_with_photo/christmas_tree_touch&gesture.html

<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/45f3ec57-00b5-4989-b3b2-484772ad95cf" />


## 🤔 Đây là gì? (Giới thiệu)

Đây không phải là một thiệp chúc mừng tĩnh trên web. Đây là một cây thông động được tạo thành từ **hàng ngàn hạt**.
Mình đã tích hợp MediaPipe của Google, nên nó có thể hiểu được cử chỉ tay của bạn.

* **Hiệu ứng hạt**: Cây có thể "thở", xoay, và còn có thể nổ tung thành bầu trời đầy sao.
* **Điều khiển từ xa**: Không cần chuột, chỉ cần vẫy tay trước camera là có thể điều khiển (cảm giác như Doctor Strange vậy).
* **Treo kỷ niệm**: Nhấn nút ở góc trên bên phải để tải ảnh lên, chúng sẽ biến thành polaroid với khung vàng, bay lơ lửng quanh cây.
* **Thẩm mỹ tối giản**: Chỉ có phối màu đen-vàng, không có trang trí rườm rà, chủ đạo là "sang trọng".

<img width="2557" height="1291" alt="image" src="https://github.com/user-attachments/assets/d7d31b4c-bf4d-49b2-b922-79813bbddba5" />

<img width="2559" height="1294" alt="image" src="https://github.com/user-attachments/assets/d7e4e982-3042-449d-8898-105048aeac1d" />


## 🛠️ Công nghệ sử dụng (Tech)

Hoàn toàn là phép thuật frontend, không dùng framework phức tạp:
* **Three.js** - Xử lý render 3D và hệ thống hạt.
* **MediaPipe** - Xử lý nhận diện cử chỉ (thứ này quá mạnh mẽ).
* **Vanilla JS (ES Modules)** - Tự viết logic cốt lõi.

## 🎮 Cách chơi? (Điều khiển)

Lần đầu chơi nên bật loa lên (dù chưa có nhạc nền, nhưng bạn có thể tự mở bài Jingle Bells 🎵).

### 🖐️ Chế độ cử chỉ (Quan trọng!)
Đảm bảo trình duyệt cho phép sử dụng camera, sau đó:
1.  **Xòe bàn tay (🖐️)**: Đây là "chế độ nổ"! Cây sẽ tách ra thành tinh vân, bạn có thể xoay góc nhìn.
2.  **Nắm chặt nắm đấm (✊)**: Thu lại! Các hạt sẽ tập hợp lại thành cây thông Noel.
3.  **Chụm ngón tay (🤏)**: Giống như đang véo thứ gì đó, nó sẽ ngẫu nhiên chọn một bức ảnh và phóng to cho bạn xem.

### 🖱️ Dùng chuột
* Kéo chuột trái để xoay, cuộn để zoom.
* **Phím H**: Nhấn để ẩn tất cả UI, rất tuyệt để chụp màn hình hoặc quay video làm hình nền.

## 🚀 Cách chạy (How to Run)

⚠️ **Lưu ý:** Vì sử dụng ES Modules và quyền truy cập camera, **ĐỪNG BAO GIỜ nhấp đúp vào `index.html` để mở**, trình duyệt sẽ báo lỗi (giới hạn chính sách CORS). Bạn cần khởi động một server local.

**Nếu bạn có VS Code (Khuyến nghị):**
Cài plugin `Live Server`, nhấp chuột phải vào `index.html` -> "Open with Live Server". Xong.

**Nếu bạn là cao thủ Python:**
Mở terminal trong thư mục:
```bash
python -m http.server 8000
```

Sau đó truy cập `localhost:8000` trên trình duyệt.

**Nếu bạn quen dùng Node.js:**

```bash
npx http-server .
```

**Merry Christmas! 🎅**
Nếu bạn thấy dự án này thú vị, hãy Star hoặc Fork và đổi thành màu bạn thích!

Đã thêm hỗ trợ web trên di động

## Contributors ✨

Cảm ơn tất cả các developer đã đóng góp cho dự án này:

<a href="https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=electronicminer/gesture-Christmas_tree-3d_with_photo" />
</a>

## 📊 Lịch sử Star

[![Star History Chart](https://api.star-history.com/svg?repos=electronicminer/gesture-Christmas_tree-3d_with_photo&type=Date)](https://star-history.com/#electronicminer/gesture-Christmas_tree-3d_with_photo&Date)
