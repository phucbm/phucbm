---
layout: post
title: "Trang blog này không có database"
description: ""
tags:
- jekyll
- github-pages
---

Phải nói là tui đã cảm thấy cực kỳ nhẹ nhõm khi tìm ra một cách khác để có thể
duy trì trang blog mà không cần đụng tới các thể loại database và hosting.

## Trước đây

Tui đã có một hai phiên bản blog được build bằng WordPress. Điều đáng buồn là
bẵng đi một thời gian không chăm sóc thì tụi nó đều biến mất đi không dấu vết.
Nếu nghe chưa đủ bi kịch, thì, tui cũng không có một bản backup
nào luôn (nô tài đáng chết 😭).

Ngày mà tui quyết định làm lại từ đầu, đó là ngày mà tui quyết tâm build một
trang blog có thể trường tồn mãi mãi theo thời gian, khi tui nói trường tồn nghĩa là
cái database, cái mà chứa cả tâm huyết tui gõ ra phải luôn nằm trong tầm mắt của tui.
Ở thời điểm hiện tại, thứ mà tui truy cập mỗi ngày, trừ mấy trang tin tức, mạng mẽo ra
thì đó là GitHub.

![Host my blog on GitHub](assets/posts/2021-09-23-trang-blog-nay-khong-co-database/googling.png "Host my blog on GitHub")

## Vấp phải Jekyll

Trước khi nhu cầu này bộc phát thì tui cũng đã có dịp tương tác với GitHub Pages.
Cộng với nhu cầu cháy bỏng đang có nữa thì cái keyword `"host my blog on github"` được sinh ra, 
và mọi thứ sau đó tuân theo _luật hoa quả_ mà tiếp diễn.

Trang blog này được build bằng Jekyll, một Static Site Generator (SSG), 
và host trên GitHub Pages trong một repo duy nhất.

Với sự kết hợp này, các bài viết sẽ được biên tập bằng file markdown, assets được
quản lý qua các folder và đường dẫn. Phần backend của blog được viết bằng Liquid, một
ngôn ngữ được tạo ra bởi Shopify và cũng không mất quá nhiều thời gian để làm quen.

![Jekyll on GitHub](assets/posts/2021-09-23-trang-blog-nay-khong-co-database/github-search-jekyll.png "Jekyll on GitHub")

Trên GitHub đã có rất nhiều repo để bạn có thể fork và sử dụng luôn. Nhưng đa số
các trang này đã được phát triển cùng với hàng loạt những tính năng mà không phải
ai cũng cần dùng tới, vì
vậy tui đã tự build một blog template from scratch.

> [Aberto - 🪄🚪👐 Static blog engine powered by Jekyll](https://github.com/phucbm/aberto).

Việc có thể tự build sản phẩm cho chính mình sử dụng đối với tui là một thú vui. Và sẽ
càng vui hơn nếu nó có thể giúp không chỉ tui mà còn nhiều người khác nữa. _Aberto_ là 
blog template được xây dựng với tiêu chí tối giản gồm những tính năng cơ bản nhất của
một trang blog và sẵn sàng để customize tuỳ theo nhu cầu.

## Kết bài ở đây

Đôi khi những thứ tưởng chừng như vô dụng ở thời điểm hiện tại lại là một 
nguyên liệu không thể thiếu để mang đến một kết quả đẹp đẽ trong tương lai.

Để tổng kết, dưới đây là những từ khoá và đường dẫn mà tui nghĩ có thể bạn sẽ muốn xem:

- [Jekyll](https://jekyllrb.com/)
- [GitHub Pages](https://pages.github.com/)
- [Liquid](https://shopify.github.io/liquid/)
- [Dillinger - Online markdown editor](https://dillinger.io/)
- [Aberto](https://github.com/phucbm/aberto)
