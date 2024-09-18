#Lý thuyết git

Git là một hệ thống quản lý phiên bản phân tán (Distributed Version Control System - DVCS) được sử dụng để theo dõi các thay đổi trong mã nguồn của dự án phần mềm. Nó giúp các nhà phát triển làm việc cùng nhau trên cùng một dự án mà không lo lắng về việc ghi đè lên công việc của nhau. Git được tạo ra bởi Linus Torvalds, người đã phát triển Linux.

**Chức năng chính của Git**:

-*Theo dõi thay đổi*: Git ghi lại lịch sử thay đổi của tệp, giúp bạn biết ai đã chỉnh sửa, chỉnh sửa cái gì, và khi nào.

-*Làm việc phân tán*: Mỗi người dùng có một bản sao đầy đủ của kho lưu trữ (repository) trên máy tính của họ, bao gồm toàn bộ lịch sử dự án. Điều này giúp Git hoạt động ngay cả khi không có kết nối mạng.

-*Nhánh (Branching)*: Git cho phép tạo ra các nhánh để phát triển các tính năng mới, sửa lỗi hoặc thử nghiệm mà không ảnh hưởng đến mã nguồn chính. Khi tính năng hoàn thành, nhánh có thể được hợp nhất (merge)trở lại nhánh chính.

-*Hợp nhất (Merging)*: Khi làm việc trên các nhánh khác nhau, Git hỗ trợ hợp nhất chúng lại với nhau mà không mất dữ liệu.

**Một số thuật ngữ quan trọng trong Git:**

-*Repository (Kho lưu trữ):* Nơi Git lưu trữ toàn bộ lịch sử thay đổi của dự án, bao gồm các commit, nhánh, và tag.

-*Commit:* Một lần ghi lại trạng thái hiện tại của dự án. Mỗi commit là một điểm trong lịch sử phát triển mã nguồn.

-*Branch (Nhánh):* Một đường dẫn phát triển độc lập, nơi bạn có thể làm việc trên các tính năng hoặc sửa lỗi mà không ảnh hưởng đến nhánh chính.

-*Merge (Hợp nhất):* Kết hợp các thay đổi từ một nhánh vào một nhánh khác.

-*Clone:* Sao chép một kho lưu trữ từ xa về máy cục bộ.

-*Push:* Gửi các thay đổi từ kho cục bộ lên kho lưu trữ từ xa (ví dụ: GitHub).

-*Pull:* Lấy các thay đổi từ kho lưu trữ từ xa về kho cục bộ.
