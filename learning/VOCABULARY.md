# Sổ từ vựng tiếng Anh chuyên ngành

[Kế hoạch](../PLAN.md) · [Checklist](../CHECKLIST.md) · [Nhật ký](LEARNING-LOG.md) · [Bài W01-S1](lessons/W01-S1.md)

**Trạng thái ban đầu:** 25 mục gợi ý, chưa mục nào được tính là đã học. Đây là ngân hàng để dùng dần trong các bài; W01-S1 chỉ tập trung năm mục đầu. Không cần học thuộc cả bảng trong một buổi.

## 1. Cách học một mục từ

1. Đọc từ trong câu/code của bài; đoán ý nếu có thể.
2. Xem nghĩa phù hợp ngữ cảnh, giải thích lại bằng tiếng Việt.
3. Che phần nghĩa và dùng một ví dụ mới để kiểm tra khả năng nhận ra.
4. Ghi ngày học, ngày ôn và lỗi nhầm. Có thể đọc thành tiếng; phần phát âm sẽ luyện riêng khi cần.

Mỗi buổi chọn 3–5 mục cần dùng, có thể gồm từ ôn. Ban đầu thêm khoảng 10–15 mục mới/tuần hoặc ít hơn nếu việc ôn còn nặng. Các câu ví dụ dưới đây do trợ giảng tự soạn; nguồn nghĩa lập trình để đối chiếu là [Python Glossary](https://docs.python.org/3/glossary.html), [Python Tutorial](https://docs.python.org/3/tutorial/) và bài học liên quan.

## 2. Ngân hàng khởi đầu

| Từ/cụm từ | Nghĩa trong ngữ cảnh lập trình | Câu ví dụ tiếng Anh | Hiểu bằng tiếng Việt | Trạng thái |
|---|---|---|---|---|
| program | chương trình | This program displays two lines. | Chương trình này hiển thị hai dòng. | Chưa học |
| instruction | chỉ dẫn/lệnh để thực hiện một thao tác | Follow the instructions in order. | Làm theo các chỉ dẫn theo thứ tự. | Chưa học |
| input | dữ liệu đầu vào | The input is a number. | Dữ liệu đầu vào là một số. | Chưa học |
| output | dữ liệu/kết quả đầu ra | Check the output. | Kiểm tra kết quả đầu ra. | Chưa học |
| run | chạy/thực thi chương trình | Run the program again. | Chạy lại chương trình. | Chưa học |
| variable | tên dùng để tham chiếu tới một giá trị/đối tượng | This variable refers to a number. | Biến này tham chiếu tới một số. | Chưa học |
| value | giá trị | The value is ten. | Giá trị là mười. | Chưa học |
| type | kiểu dữ liệu | Check the type of this value. | Kiểm tra kiểu của giá trị này. | Chưa học |
| string | chuỗi ký tự | This string contains a word. | Chuỗi này chứa một từ. | Chưa học |
| number | số | Add the two numbers. | Cộng hai số lại. | Chưa học |
| boolean | giá trị đúng/sai | The result is a boolean. | Kết quả là một giá trị đúng/sai. | Chưa học |
| condition | điều kiện | Check the condition first. | Kiểm tra điều kiện trước. | Chưa học |
| loop | vòng lặp | This loop visits every item. | Vòng lặp này đi qua từng phần tử. | Chưa học |
| function | hàm | Call the function with a number. | Gọi hàm với một số. | Chưa học |
| argument | đối số được truyền vào khi gọi hàm | Pass this value as an argument. | Truyền giá trị này làm đối số. | Chưa học |
| return | trả giá trị về nơi gọi hàm | Return the result to the caller. | Trả kết quả về nơi gọi. | Chưa học |
| list | danh sách trong Python | The list contains three items. | Danh sách chứa ba phần tử. | Chưa học |
| dictionary | cấu trúc ánh xạ khóa tới giá trị | Store the meaning in a dictionary. | Lưu nghĩa vào một từ điển dữ liệu. | Chưa học |
| key | khóa để truy cập giá trị trong ánh xạ | Use the word as the key. | Dùng từ làm khóa. | Chưa học |
| index | chỉ số vị trí | The first index is zero. | Chỉ số đầu tiên là không. | Chưa học |
| length | độ dài/số phần tử theo đối tượng | Find the length of the list. | Tìm số phần tử của danh sách. | Chưa học |
| error | lỗi được quan sát hoặc báo khi xử lý | Read the error message. | Đọc thông báo lỗi. | Chưa học |
| bug | sai sót trong chương trình | This bug gives the wrong result. | Sai sót này làm kết quả bị sai. | Chưa học |
| debug | tìm và sửa lỗi | Debug the program step by step. | Tìm và sửa lỗi từng bước. | Chưa học |
| test case | một ca/trường hợp kiểm tra | Add a test case for empty input. | Thêm ca kiểm tra với đầu vào rỗng. | Chưa học |

**Những chỗ dễ nhầm:** `return` khác `print` — trả giá trị khác hiển thị; `argument` trong code là đối số, không phải cuộc tranh luận; `list` của Python không có nghĩa là linked list; `dictionary` ở đây là cấu trúc dữ liệu, dù dự án có thể dùng nó để làm sổ từ vựng. Một dòng code không nhất thiết tương ứng một lệnh máy.

`The first index is zero` dùng cho cách đánh chỉ số của Python trong bài học, không khẳng định mọi ngôn ngữ đều như vậy. Một lỗi logic có thể cho kết quả sai mà không hiện thông báo lỗi; đọc được thông báo chỉ là một phần của việc debug.

## 3. Mẫu thêm từ mới

| Mã/buổi | Từ/cụm từ | Nghĩa trong bài | Câu ví dụ và bản hiểu tiếng Việt | Nguồn |
|---|---|---|---|---|
| — | Chưa có mục bổ sung | — | — | — |

Giữ những cụm từ đọc đề như `at least` (ít nhất), `at most` (nhiều nhất), `in place` (xử lý tại chỗ, cần xem rõ định nghĩa bộ nhớ của bài), `on average` (tính trung bình), `worst case` (trường hợp xấu nhất) khi chúng xuất hiện. Không học các bản dịch tách rời điều kiện kỹ thuật.

## 4. Bảng ôn theo ngày thực học

Quy ước trạng thái: **Chưa học** → **Cần gợi ý** → **Nhận ra độc lập** → **Đã ôn lại**. “Đã ôn lại” chỉ ghi khi đã thử nhớ trong một lần khác; vẫn có thể quay về “Cần gợi ý” khi quên.

| Từ/cụm từ | Ngày học | Ôn gần nhất | Kết quả trong câu mới | Ôn tiếp | Nhầm cần sửa |
|---|---|---|---|---|---|
| — | Chưa bắt đầu | — | — | — | — |

Có thể thử ôn sau 1, 3, 7, 14 và 30 ngày. Đây là lịch thực hành gợi ý, không phải thông báo tự động. Ghi ngày thật sau khi học; không điền toàn bộ ngày theo ngày tạo tệp.

## 5. Kiểm tra cuối tuần

Trợ giảng chọn năm mục đã học và đưa chúng vào câu mới; người học giải thích nghĩa bằng tiếng Việt. Khi tự học, dùng câu mới từ tài liệu có nguồn. Tự viết câu là phần luyện tùy chọn. Mục tiêu ban đầu: hiểu đúng ít nhất 4/5, đồng thời tóm tắt đúng đoạn đọc của tuần. Đọc lại nghĩa khi vướng, ghi mục cần ôn rồi thử lại. Không cộng số từ trong bảng thành “vốn từ đã biết”.
