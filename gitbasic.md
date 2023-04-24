# 1. Git Basic  

- Các bạn chỉ cần biết được Git căn bản là có thể tự quản lý code của bản thân mình rồi. Trong chương này, mình sẽ hướng dẫn mọi người Git căn bản và nâng cao.
- Bắt buộc các bạn cần phải hiểu và thao tác được với Git căn bản để có thể push source code lên github phục vụ mục đích deploy cũng như review fix lỗi. Còn Git nâng cao thì sẽ áp dụng khi các bạn muốn tùy chỉnh nhiều hơn hoặc sau này đi làm, nên là nếu bạn muốn xin vào các vị trí Junior, Senior thì Git nâng cao là yêu cầu cần thiết phải biết.

##1. Config name và email cho git với git config
 - Git có 2 loại config đó là local và global. Local là dành riêng cho dự án, còn Global là cho cả máy tính, nếu không config local thì Git sẽ tự động dùng config của global.
 - Để xem các config ở local

##3. Hiển thị trạng thái với 'git status '

câu lệnh này sẽ hiển thị
- Bạn đang ở branch nào

##4 Các khu vực làm việc với git
chúng ta sẽ làm theo như sau
1. **Khu vực làm việc với git**: chính là nơi chúng ta đang code, vẫn ở local
2. **Khu vực staging**: Sau khi dùng `git add` thì file sẽ được đưa lên khu vực này, vẫn ở trên local
