# Hồn Việt — xuất bản riêng github.io, 24-10-2026

Chủ dự án yêu cầu chỉ Hồn Việt dùng github.io; giữ domain lessbyte.app của các app khác. Quyết định này thay URL lessbyte.app trước đó cho Hồn Việt.

Nguồn biên tập duy nhất vẫn là docs/apps/hon-viet trong khoanguyen1192/khoabao-store. Đích xuất bản là site xác minh công khai đã có khoanguyen1192/khoanguyen1192.github.io, Pages main:/, cname null. Không tạo repo hay site mới; không thay CNAME/DNS của site dùng chung. Đây là ngoại lệ hosting theo yêu cầu cụ thể của chủ dự án đối với quy tắc deploy cùng repo trong delivery.md; repo đích chỉ nhận bản xuất giống byte của thư mục Hồn Việt, không trở thành bản biên tập song song.

URL chuẩn mới:
- https://khoanguyen1192.github.io/apps/hon-viet/
- https://khoanguyen1192.github.io/apps/hon-viet/support/
- https://khoanguyen1192.github.io/apps/hon-viet/privacy/

Mỗi lần cập nhật: sửa nguồn ở repo này, xuất nguyên thư mục docs/apps/hon-viet sang apps/hon-viet của repo đích, so SHA, commit chỉ thư mục đó, kiểm Pages build và mở live. Giữ nguyên root index.html và app-ads.txt của repo đích. Site cũ giữ phục vụ liên kết lịch sử; canonical Hồn Việt trỏ github.io. Không redirect hoặc di chuyển toàn bộ portfolio.

Đổi URL App Store và native sau khi live đã được xác nhận. Không đồng nghĩa duyệt nội dung hoặc submit.
