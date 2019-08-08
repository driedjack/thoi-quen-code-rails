# Thói quen code Rails

*Xây dựng thói quen lập trình Ruby on Rails từ những điều nhỏ nhặt hằng ngày.*

Với việc code hằng ngày, ta không muốn phải đắn đo suy nghĩ hoặc lựa chọn những điều mà lâu dần ta xem nó như một thói quen hay phong cách tốt cho ta và những dự án ta làm. Thế nên tôi lập ra danh sách những điều sẽ được lặp lại thường xuyên, được áp dụng hầu hết cho mọi dự án, những kiểu viết code, cách đặt hay dùng code,... và gọi chúng là thói quen tốt khi code. Tất cả đều được tìm hiểu, nghiên cứu và so sánh. Tất nhiên, mọi thứ chỉ là tương đối, nó có thể tốt trong trường hợp này nhưng ngược lại với trường hợp khác, nên vì vậy điều quan trong vẫn là tuỳ trường hợp mà dùng, tuỳ cơ mà hành sự.

Mục tiêu cuối cùng cốt giúp cho việc lập trình Ruby on Rails nhẹ nhàng và vui vẻ hơn.

---

## Nên comment dòng `frozen_string_literal: true` đầu mỗi file ruby

- Để đóng băng tất cả chuỗi của file đó và một phần tăng performance cho ứng dụng.

- Ví dụ: trong file `application_controller.rb`

```ruby
# frozen_string_literal: true

class ApplicationController < ActionController::Base
end
```
