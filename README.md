
# 🎄 Cây Thông Sang Trọng

[![Contributors](https://img.shields.io/github/contributors/electronicminer/gesture-Christmas_tree-3d_with_photo?color=dark-green)](https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors)

Xin chào! Đây là một dự án nhỏ được viết để chúc mừng Giáng sinh. ✨

Ban đầu chỉ muốn vẽ một cây thông 3D bình thường, nhưng cảm thấy chưa đủ thú vị, nên đã thêm **nhận diện cử chỉ** và **hiệu ứng hạt**. Bây giờ bạn có thể điều khiển cây này "từ xa" qua camera và treo những bức ảnh yêu thích của mình lên.

Mặc dù chỉ có vài trăm dòng code, nhưng hiệu ứng hình ảnh rất ấn tượng (đặc biệt là trên màn hình lớn).

Nhấp vào liên kết bên dưới để truy cập trực tiếp:
[Truy cập dự án tại đây](https://tovanhieu.github.io/pine-tree-GestureControl-Mediapine/)

<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/45f3ec57-00b5-4989-b3b2-484772ad95cf" />


## 🤔 Đây là gì? (Giới thiệu)

Đây không phải là một tấm thiệp web tĩnh. Đây là một cây động được tạo thành từ **hàng nghìn hạt**.
Tôi đã tích hợp MediaPipe của Google, vì vậy nó có thể hiểu cử chỉ của bạn.

* **Hiệu ứng hạt**：Cây sẽ thở, xoay và có thể nổ tung thành những ngôi sao.
* **Điều khiển từ xa**：Không cần chuột, chỉ cần vẫy tay trước camera là có thể điều khiển (cảm giác như Doctor Strange).
* **Treo kỷ niệm**：Nhấp vào nút ở góc trên bên phải để tải ảnh lên, chúng sẽ trở thành những tấm ảnh Polaroid có khung vàng, bay xung quanh cây.
* **Thẩm mỹ tối giản**：Chỉ có màu đen và vàng, không có trang trí rườm rà, tập trung vào "cảm giác cao cấp".
<img width="2557" height="1291" alt="image" src="https://github.com/user-attachments/assets/d7d31b4c-bf4d-49b2-b922-79813bbddba5" />

<img width="2559" height="1294" alt="image" src="https://github.com/user-attachments/assets/d7e4e982-3042-449d-8898-105048aeac1d" />


## 🛠️ Sử dụng công nghệ gì? (Công nghệ)

Hoàn toàn là frontend, không sử dụng framework phức tạp:
* **Three.js** - Xử lý render 3D và hệ thống hạt.
* **MediaPipe** - Xử lý nhận diện cử chỉ (công cụ này rất mạnh).
* **JavaScript thuần (ES Modules)** - Viết logic cốt lõi bằng tay.

## 🎮 Cách chơi? (Điều khiển)

Lần đầu chơi nên bật loa (mặc dù chưa có nhạc nền, nhưng bạn có thể tự bật bài Jingle Bells 🎵).

### 🖐️ Chế độ cử chỉ (Quan trọng!)
Đảm bảo trình duyệt cho phép sử dụng camera, sau đó:
1.  **Mở lòng bàn tay (🖐️)**：Đây là "chế độ nổ tung"! Cây sẽ tách ra thành tinh vân, bạn có thể xoay góc nhìn.
2.  **Nắm chặt tay (✊)**：Thu lại! Các hạt sẽ tái tụ lại thành cây thông.
3.  **Chụm ngón tay (🤏)**：Giống như đang véo một thứ gì đó, nó sẽ ngẫu nhiên chọn một bức ảnh và phóng to cho bạn xem.

### 🖱️ Dùng chuột
* Kéo trái để xoay, cuộn để phóng to/thu nhỏ.
* **Phím H**：Nhấn để ẩn tất cả UI, rất tốt để chụp màn hình hoặc quay video làm hình nền.

## 🚀 Chạy dự án (Cách chạy)

⚠️ **Lưu ý：** Vì sử dụng ES Modules và quyền truy cập camera, **tuyệt đối không được mở trực tiếp bằng cách double-click vào `index.html`**, trình duyệt sẽ báo lỗi (giới hạn chính sách CORS). Bạn phải khởi động một máy chủ local.

**Nếu bạn có VS Code (Khuyến nghị):**
Cài đặt plugin `Live Server`, nhấp chuột phải vào `index.html` -> "Open with Live Server". Xong.

**Nếu bạn dùng Python:**
Mở terminal trong thư mục:
```bash
python -m http.server 8000
```

Sau đó truy cập `localhost:8000` trên trình duyệt.

**Nếu bạn quen với Node.js:**

```bash
npx http-server .
```



**Merry Christmas! 🎅**
Nếu bạn thấy dự án này thú vị, hãy Star, hoặc Fork và sửa thành màu bạn thích!

Đã thêm hỗ trợ trang web di động
## Contributors ✨

Cảm ơn tất cả các nhà phát triển đã đóng góp cho dự án này:

<a href="https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=electronicminer/gesture-Christmas_tree-3d_with_photo" />
</a>

## 📊 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=electronicminer/gesture-Christmas_tree-3d_with_photo&type=Date)](https://star-history.com/#electronicminer/gesture-Christmas_tree-3d_with_photo&Date)
