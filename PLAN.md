# Kế hoạch học lập trình và tiếng Anh chuyên ngành

**Phiên bản:** 1.0 · **Ngày lập:** 20/10/2026 · **Trạng thái:** sẵn sàng bắt đầu, chưa đánh giá đầu vào.

**Mục tiêu:** học lại nền tảng lập trình, hiểu các chủ đề cốt lõi được chọn từ Coding Interview University, đồng thời đọc hiểu tiếng Anh trong ngữ cảnh công nghệ và tự giải thích cách làm.

**Bắt đầu:** [Bài W01-S1](learning/lessons/W01-S1.md) → [Checklist tuần W01](CHECKLIST.md#w01). **Theo dõi:** [Nhật ký học](learning/LEARNING-LOG.md) · [Sổ từ vựng](learning/VOCABULARY.md).

## 1. Những lựa chọn của kế hoạch

| Nội dung | Quyết định ban đầu | Khi nào điều chỉnh? |
|---|---|---|
| Ngôn ngữ giảng giải | Tiếng Việt; thuật ngữ tiếng Anh luôn đi cùng nghĩa và ví dụ | Tăng phần đọc tiếng Anh khi người học đã hiểu nội dung |
| Ngôn ngữ thực hành | Python 3; tên biến/hàm ngắn, có nghĩa | Sau đánh giá đầu vào nếu đã thành thạo ngôn ngữ khác |
| Nền tảng lập trình và tiếng Anh | Chưa xác định; khảo sát bằng bài làm, không tự gán trình độ | Cuối W01 và W02 |
| Thời gian | Nhịp mẫu 8 giờ/tuần, gồm cả tiếng Anh và ôn tập | Dựa trên giờ học thực tế sau hai tuần |
| Phạm vi | 48 tuần học, 12 chặng, 240 buổi; có chọn lọc và bổ sung bài nền tảng | Cuối mỗi chặng bốn tuần |
| Tiến độ | Kỹ thuật và tiếng Anh được ghi riêng | Chỉ cập nhật khi có bằng chứng |
| Công cụ | Python, trình soạn thảo, Git/GitHub; ưu tiên thư viện chuẩn | Cài công cụ khác khi bài học có nhu cầu cụ thể |

**8 giờ/tuần là đề xuất của kế hoạch này, chưa phải thời gian người học đã cam kết.** Các tuần là đơn vị khối lượng, không gắn cứng với tuần lịch. 48 × 8 = **384 giờ dự kiến ban đầu**, gồm thực hành, đọc, ôn và đánh giá. Thời gian thực tế có thể tăng đáng kể nếu cần củng cố nền tảng hoặc học lại các chủ đề khó. Không dùng con số này để hứa hoàn thành mọi nội dung CIU hoặc đạt mức sẵn sàng tuyển dụng.

| Giờ học thực tế mỗi tuần | Số tuần lịch tương đương cho 384 giờ, chưa tính nghỉ và học bù |
|---|---:|
| 4 giờ | 96 tuần |
| 6 giờ | 64 tuần |
| 8 giờ | 48 tuần |

Repo gốc yêu cầu đã biết một ít về biến, vòng lặp và hàm, tập trung chuẩn bị nền tảng cho phỏng vấn kỹ thuật. Kế hoạch này thêm W01–W08 để người học có thể bắt đầu từ nền tảng; đưa đệ quy lên trước cây/đồ thị; thêm bài ứng dụng và tiếng Anh. Xem [điều kiện đầu vào](README.md#what-is-it), [lựa chọn ngôn ngữ](README.md#choose-a-programming-language) và [phạm vi repo](README.md#what-you-wont-see-covered).

Python được chọn để tập trung vào tư duy và giảm lượng cú pháp cần học ban đầu. Đây là lựa chọn sư phạm của lộ trình. Đến phần bộ nhớ, dùng sơ đồ và đoạn C ngắn có giải thích; việc thành thạo C thuộc phần mở rộng. Python Tutorial là tài liệu tra cứu có hướng dẫn: [chính tài liệu này cũng nêu điều kiện đã hiểu lập trình cơ bản](https://docs.python.org/3/tutorial/), vì vậy người mới học qua các bài nhỏ trước.

## 2. Cách tổ chức một tuần

| Buổi | Thời lượng | Công việc chính | Sản phẩm |
|---|---:|---|---|
| S1 | 90 phút | Hiểu khái niệm, ví dụ trực quan, đọc đoạn tiếng Anh ngắn | Giải thích bằng lời và bảng mô phỏng |
| S2 | 90 phút | Viết chương trình hoặc mô hình đầu tiên có hướng dẫn | Code/ghi chú và kết quả chạy |
| S3 | 90 phút | Tự giải bài tập, kiểm tra dữ liệu thông thường và dữ liệu biên | Bài làm độc lập và các ca kiểm tra |
| S4 | 90 phút | Làm biến thể, áp dụng vào bài nhỏ, củng cố tiếng Anh | Lời giải mới hoặc cải tiến có giải thích |
| S5 | 120 phút | Ôn cách quãng, đánh giá kỹ thuật + tiếng Anh, sửa lỗi, cập nhật tiến độ | Bằng chứng, lỗi cần sửa và việc học tiếp |

S1–S4 có thể chia thành hai phiên 45 phút. Mỗi buổi 90 phút thường gồm: 10 phút nhớ lại bài cũ; 15 phút đọc/từ vựng; 25 phút học khái niệm và mô phỏng; 30 phút thực hành; 10 phút tự kiểm tra và ghi nhật ký. Đây là phân bổ gợi ý, có thể đổi theo loại bài. Riêng W01-S1 dành 40 phút khảo sát và 50 phút học bài đầu tiên.

Trong S5, ưu tiên 20 phút nhớ lại; 45 phút bài kiểm tra kỹ thuật; 20 phút đọc/từ vựng; 25 phút sửa lỗi; 10 phút cập nhật. Tuần có bài dự án dùng sản phẩm và phần giải thích làm bằng chứng. Không cộng thêm một lịch tiếng Anh riêng ngoài tám giờ.

## 3. Cách tôi sẽ dạy từng bài

1. **Nêu một mục tiêu nhỏ:** sau bài này giải thích hoặc làm được việc gì.
2. **Giải thích bằng tiếng Việt:** định nghĩa, ví dụ đời thường và hình/bảng mô phỏng khi cần.
3. **Đưa 3–5 từ hoặc cụm từ vào ngữ cảnh:** nghĩa trong bài, câu tiếng Anh, cách hiểu tiếng Việt; giảm từ mới khi lượng ôn còn nhiều.
4. **Làm mẫu một ví dụ:** dự đoán trước, chạy hoặc mô phỏng sau; giải thích từng bước.
5. **Để bạn tự làm:** từ bài gần giống đến một biến thể nhỏ; gợi ý từng mức khi vướng.
6. **Phản hồi cụ thể:** đúng ở đâu, sai vì hiểu thuật ngữ hay sai về kỹ thuật, cần sửa thao tác nào.
7. **Lưu bằng chứng và bài tiếp theo:** dùng mã Wxx-Sy để dễ tiếp tục qua các cuộc trò chuyện.

Ví dụ cách yêu cầu học: **“Dạy tôi W01-S1 theo PLAN.md, giải thích bằng tiếng Việt.”** Khi nộp bài, gửi mã buổi và bài làm. Khi tiếp tục, dùng **“Đọc CHECKLIST.md và nhật ký, dạy tôi buổi tiếp theo.”** Các mã buổi là định danh ổn định, kể cả khi một tuần học kéo dài qua nhiều tuần lịch.

Chỉ W01-S1 đã được viết thành giáo án đầy đủ ở phiên bản này. Những buổi còn lại có mục tiêu, nhiệm vụ, nguồn và đầu ra trong checklist; giáo án chi tiết được phát triển khi đến buổi học, căn cứ bài làm trước đó. Có thể tự thực hành theo các nhiệm vụ sẵn có mà không chờ toàn bộ giáo án được viết xong.

## 4. Khảo sát đầu vào và cách rút ngắn bài đã biết

Khảo sát W01-S1 gồm đọc/dự đoán một đoạn code, sửa một lỗi nhỏ, mô tả bài toán và cách giải bằng tiếng Việt, rồi đọc đoạn tiếng Anh ngắn. Không biết thì ghi “chưa biết”; không cần đoán hoặc dùng AI làm thay. Chưa có Python vẫn có thể đọc và dự đoán; việc cài/chạy thực tế được làm ở W01-S2.

| Kết quả quan sát | Cách học tiếp |
|---|---|
| Chưa quen chạy chương trình, biến, vòng lặp, hàm | Đi đủ W01–W08, chia nhỏ bài khi cần |
| Viết được bài cơ bản nhưng khó giải thích hoặc kiểm tra | Rút ngắn phần giảng, giữ thực hành và đánh giá |
| Đã làm độc lập và giải thích được chủ đề | Làm bài kiểm tra thay thế: bài mới, trường hợp biên, thuật ngữ trong ngữ cảnh |
| Hiểu kỹ thuật nhưng đọc tiếng Anh chậm | Tiếp tục kỹ thuật phù hợp; giữ đoạn đọc ngắn và ôn từ trọng tâm |
| Đọc tốt nhưng kỹ thuật chưa vững | Tăng độ khó đoạn đọc theo chủ đề đang học; củng cố kỹ thuật tiên quyết |

Không tự đánh dấu các tuần là đạt chỉ vì đã từng học một khóa khác. Khi rút ngắn, ghi ngày, bài kiểm tra thay thế và kết quả trong nhật ký; các buổi thực sự đã thực hiện mới được tính vào số buổi học. Tiến độ năng lực của tuần có thể đạt trước khi học đủ năm buổi.

## 5. Lộ trình 12 chặng

| Chặng | Tuần | Trọng tâm | Bằng chứng cuối chặng |
|---|---|---|---|
| M00 | W01–W04 | Cách chương trình hoạt động; biến, điều kiện, vòng lặp, hàm | Viết chương trình nhỏ từ yêu cầu tiếng Việt, đọc và sửa lỗi cơ bản |
| M01 | W05–W08 | Danh sách, từ điển, tệp, lỗi, kiểm thử, đối tượng | Vocabulary Notebook v1: lưu, tìm và hiển thị từ vựng |
| M02 | W09–W12 | Thuật toán, độ phức tạp, đệ quy, tìm kiếm nhị phân, bit | Mô phỏng và giải thích chi phí của các cách giải |
| M03 | W13–W16 | Mảng động, danh sách liên kết, ngăn xếp, hàng đợi, bảng băm | Tự xây cấu trúc dữ liệu ở mức học tập, kiểm tra thao tác và dữ liệu biên |
| M04 | W17–W20 | Sắp xếp và các mẫu giải bài trên dãy | Giải bài biến thể, biết khi nào một mẫu giải không áp dụng |
| M05 | W21–W24 | Cây nhị phân, cây tìm kiếm, heap, trie | Duyệt/tìm/cập nhật và giải thích lựa chọn cấu trúc |
| M06 | W25–W28 | Đồ thị, BFS/DFS, đường đi ngắn, cây khung | Chọn thuật toán theo loại đồ thị và điều kiện của bài |
| M07 | W29–W32 | Quay lui, quy hoạch động, tham lam | Tự xác định trạng thái, điều kiện dừng và phản ví dụ |
| M08 | W33–W36 | Toán rời rạc cơ bản, độ khó bài toán, tìm chuỗi, Unicode, ôn | Giải thích ý tưởng và xử lý văn bản đúng trên ví dụ nhỏ |
| M09 | W37–W40 | CPU, bộ nhớ, cache, tiến trình/luồng, mạng | Mô tả chương trình và dữ liệu đi qua hệ thống như thế nào |
| M10 | W41–W44 | Kiểm thử, tổ chức code, thiết kế, cache, chuẩn bị dự án | Thiết kế rõ yêu cầu và chạy được một luồng mẫu của v2 |
| M11 | W45–W48 | Ôn hỗn hợp, bài mới, hoàn thiện dự án, đánh giá | Code, demo, tài liệu và đánh giá độc lập hai năng lực |

### Kế hoạch từng tuần

Mỗi dòng dưới đây dẫn đến **năm nhiệm vụ theo buổi, từ vựng, nguồn học, đầu ra và tiêu chí đạt** trong CHECKLIST.md. Nếu một chủ đề vượt quá thời gian mẫu, hoàn thành phần tiên quyết rồi mới đi tiếp.

| Tuần | Chủ đề | Sản phẩm cụ thể |
|---|---|---|
| [W01](CHECKLIST.md#w01) | Bắt đầu: chương trình, dữ liệu vào/ra và môi trường học | hello.py chạy được, ghi chú môi trường và kết quả khảo sát; có một commit chứa bài tập, kèm cách chạy và kết quả của hai biến thể. |
| [W02](CHECKLIST.md#w02) | Biến, kiểu dữ liệu và toán tử | time_converter.py và bảng dự đoán/kết quả cho 0, 59, 60, 61 và 125 phút; ghi rõ chỉ nhận số nguyên không âm ở phiên bản này. |
| [W03](CHECKLIST.md#w03) | Điều kiện, vòng lặp và mô phỏng chương trình | number_loops.py, bảng mô phỏng n = 5 và kiểm tra n = 0, 1, 5, -1; bản âm phải được báo không hợp lệ thay vì âm thầm tính sai. |
| [W04](CHECKLIST.md#w04) | Hàm, phạm vi biến, sửa lỗi và kiểm tra M00 | basic_functions.py, sáu kiểm tra có kết quả mong đợi và nhật ký sửa hai lỗi; lưu bài kiểm tra M00 tách khỏi ví dụ đã xem. |
| [W05](CHECKLIST.md#w05) | List, tuple, chuỗi và thao tác trên dãy | word_list_tools.py gồm lọc theo độ dài, tìm từ dài nhất và ghép chuỗi; kiểm tra dãy rỗng, một từ, độ dài bằng ngưỡng và nhiều từ đồng hạng. |
| [W06](CHECKLIST.md#w06) | Dictionary, set và thống kê văn bản | word_frequency.py và mẫu văn bản tự tạo; kiểm tra chuỗi rỗng, từ lặp, chữ hoa/thường, dấu câu trong quy tắc và tra cứu từ chưa có. |
| [W07](CHECKLIST.md#w07) | File, JSON, module, ngoại lệ và kiểm tra tự động | vocabulary_store.py và test_vocabulary_store.py; kiểm tra lưu/đọc tiếng Việt, dữ liệu rỗng, file chưa có và JSON sai định dạng trên file tạm. |
| [W08](CHECKLIST.md#w08) | Class, object, tham chiếu và Vocabulary Notebook CLI v1 | Vocabulary Notebook CLI v1 chạy bằng thư viện chuẩn, lưu JSON và hướng dẫn sử dụng; kiểm tra thêm/tìm từ, từ trùng, đầu vào rỗng và dữ liệu còn sau khi mở lại. |
| [W09](CHECKLIST.md#w09) | Thuật toán, Big-O và logarithm bằng ví dụ trực quan | complexity_notes.md với bảng đếm và phân tích bốn đoạn code; có một đoạn chia đôi, một vòng lặp đơn, một vòng lặp lồng và một phép truy cập trực tiếp. |
| [W10](CHECKLIST.md#w10) | Đệ quy, điều kiện dừng và ngăn xếp lời gọi | recursion_basics.py và sơ đồ factorial(4); kiểm tra factorial(0) = 1, factorial(5) = 120, dữ liệu âm bị từ chối và tổng khớp bản vòng lặp. |
| [W11](CHECKLIST.md#w11) | Tìm kiếm nhị phân và quản lý ranh giới | binary_search.py gồm bản lặp và đệ quy, quy ước trả -1 nếu thiếu; trường hợp trùng chấp nhận bất kỳ chỉ số khớp nào trong miền hợp lệ. |
| [W12](CHECKLIST.md#w12) | Bit, bù hai 8 bit và kiểm tra M02 | bits_8bit.py và bảng mã hóa/giải mã -128, -1, 0, 127; minh họa 127 + 1 trong Python khác phép cộng được giới hạn 8 bit. |
| [W13](CHECKLIST.md#w13) | Tự xây dynamic array: size, capacity và đổi vùng chứa | dynamic_array.py dùng buffer có độ dài cố định giữa các lần resize, capacity tối thiểu 16; kiểm tra truy cập, thêm/xóa đầu/cuối/giữa và bảo toàn dữ liệu khi đổi buffer. |
| [W14](CHECKLIST.md#w14) | Danh sách liên kết đơn và thao tác trên node | singly_linked_list.py tự dùng Node; kiểm tra thêm đầu/cuối, lấy đầu, tìm, xóa theo chỉ số và đảo, kèm sơ đồ tham chiếu trước/sau. |
| [W15](CHECKLIST.md#w15) | Stack, queue và bộ đệm vòng | stack_queue.py, circular_buffer.py và hai ví dụ sử dụng; kiểm tra buffer rỗng, đầy, quay vòng, xen kẽ thêm/lấy cùng trường hợp ngoặc đóng thiếu mở. |
| [W16](CHECKLIST.md#w16) | Tự xây hash table bằng chaining và kiểm tra M03 | chained_hash_table.py với put/get/contains/remove và rehash; bộ kiểm tra ép va chạm, khóa trùng, khóa thiếu, xóa trong bucket và giữ dữ liệu khi mở rộng. |
| [W17](CHECKLIST.md#w17) | Selection sort, insertion sort và tính ổn định | elementary_sorts.py, bảng trace sáu số và ví dụ bản ghi đồng khóa; kiểm tra dãy rỗng, một phần tử, trùng, đã tăng và đã giảm. |
| [W18](CHECKLIST.md#w18) | Merge sort, quicksort và lựa chọn thuật toán sắp xếp | divide_conquer_sorts.py và bảng so sánh bốn thuật toán; kiểm tra dãy rỗng, trùng hoàn toàn, tăng, giảm và dữ liệu hỗn hợp bằng kết quả sorted đối chiếu. |
| [W19](CHECKLIST.md#w19) | Mẫu two pointers: hai chỉ số duyệt | two_pointers.py gồm kiểm tra đối xứng, tìm cặp trên dãy tăng và loại trùng tại chỗ; có mô phỏng chỉ số và kiểm tra không đáp án, trùng, rỗng. |
| [W20](CHECKLIST.md#w20) | Sliding window, prefix sum và kiểm tra M04 | window_prefix.py với ba hàm và bản vét cạn đối chiếu; kiểm tra k = 1, k = n, k không hợp lệ, mục tiêu không đạt và truy vấn khoảng rỗng. |
| [W21](CHECKLIST.md#w21) | Cây nhị phân và duyệt DFS/BFS | binary_tree.py với bốn phép duyệt, đếm node, tính chiều cao; kiểm tra rỗng, một node, cây lệch và cây có giá trị trùng bằng thứ tự đã tính tay. |
| [W22](CHECKLIST.md#w22) | BST: tìm, thêm, xóa và ý tưởng cân bằng | binary_search_tree.py với search/insert/delete, min/max và kiểm tra tính chất bằng giới hạn khóa; thử xóa lá, một con, hai con, gốc và khóa không tồn tại. |
| [W23](CHECKLIST.md#w23) | Heap, hàng đợi ưu tiên và heapsort | binary_heap.py và heap_sort.py tự cài lõi; kiểm tra bất biến sau chèn/lấy, heapify bảo toàn phần tử, heapsort khớp sorted trên rỗng, trùng, tăng và giảm. |
| [W24](CHECKLIST.md#w24) | Trie, tìm theo tiền tố và kiểm tra M05 | trie.py và Vocabulary Notebook có tìm theo tiền tố; kiểm tra 'co' là tiền tố nhưng chưa là từ, từ trùng, tiền tố thiếu, giới hạn kết quả và dữ liệu tiếng Việt. |
| [W25](CHECKLIST.md#w25) | Biểu diễn đồ thị và duyệt theo chiều rộng (BFS) | Một đồ thị có hai cách biểu diễn, hàm BFS trả khoảng cách và đường đi, sáu trường hợp kiểm tra cùng ghi chú từ vựng. |
| [W26](CHECKLIST.md#w26) | Duyệt sâu (DFS), chu trình, thành phần liên thông và thứ tự phụ thuộc | Hàm DFS, đếm thành phần liên thông và sắp thứ tự phụ thuộc; dữ liệu sáu môn học; sáu ca kiểm tra có cả chu trình. |
| [W27](CHECKLIST.md#w27) | Đường đi ngắn nhất có trọng số: Dijkstra và giới hạn áp dụng | Hàm Dijkstra với sáu ca kiểm tra, một bảng chạy tay và bảng lựa chọn BFS hoặc Dijkstra; ghi chú ý tưởng Bellman–Ford. |
| [W28](CHECKLIST.md#w28) | Cây khung nhỏ nhất với Prim và kiểm tra M06 | Hàm Prim, ba đồ thị tính tay, bảng chọn bốn thuật toán và bài kiểm tra M06. Thành phần liên thông mạnh, kiểm tra hai phía chỉ học thêm khi còn thời gian. |
| [W29](CHECKLIST.md#w29) | Quay lui (backtracking): sinh tập con và hoán vị | Hai hàm sinh tập con và hoán vị với đầu vào không trùng; sơ đồ nhánh cho ba phần tử và năm ca kiểm tra. |
| [W30](CHECKLIST.md#w30) | Quy hoạch động: ghi nhớ kết quả và lập bảng | Hai cách giải Fibonacci, hai cách giải leo cầu thang, bảng trạng thái và kết quả đối chiếu trên mười đầu vào nhỏ. |
| [W31](CHECKLIST.md#w31) | Quy hoạch động: đổi tiền và ba lô 0/1 ở quy mô nhỏ | Hai lời giải quy hoạch động, bảng tính tay cho mỗi bài và bộ đối chiếu với cách vét cạn trên dữ liệu nhỏ. |
| [W32](CHECKLIST.md#w32) | Tham lam, phản ví dụ và kiểm tra M07 | Hàm chọn cuộc hẹn, phản ví dụ đổi tiền, bảng phân loại bốn bài và bài kiểm tra M07 có lời giải thích. |
| [W33](CHECKLIST.md#w33) | Tổ hợp và xác suất cơ bản để hiểu số cách và mô phỏng | Năm bài tính có giả định, mã mô phỏng và bảng so sánh lý thuyết với ba cỡ mẫu; dữ liệu hoàn toàn tự tạo. |
| [W34](CHECKLIST.md#w34) | P, NP, NP đầy đủ và thuật toán xấp xỉ ở mức khái niệm | Một trang giải thích P, NP và NP đầy đủ bằng tiếng Việt; năm nhận định có sửa lỗi; ví dụ quyết định và tối ưu hóa. |
| [W35](CHECKLIST.md#w35) | Tìm chuỗi con, ý tưởng KMP và văn bản Unicode | Hàm tìm chuỗi đơn giản, bảy ca kiểm tra gồm văn bản tiếng Việt, một mô phỏng KMP và ví dụ Unicode trước, sau chuẩn hóa. |
| [W36](CHECKLIST.md#w36) | Ôn thuật toán qua công cụ phân tích văn bản và kiểm tra M08 | Công cụ phân tích văn bản nhỏ với dữ liệu mẫu, sáu ca kiểm tra, ghi chú giả định và bài kiểm tra M08. |
| [W37](CHECKLIST.md#w37) | Máy tính chạy chương trình: CPU, bộ nhớ, tham chiếu và con trỏ | Sơ đồ CPU và bộ nhớ, ghi chú đoạn C minh họa, ba dự đoán Python đã chạy kiểm chứng; không tạo dự án bằng ngôn ngữ thứ hai. |
| [W38](CHECKLIST.md#w38) | Bộ nhớ đệm CPU, tính cục bộ, số thực và thứ tự byte | Sơ đồ bộ nhớ, ví dụ sai số số thực, thí nghiệm thứ tự byte bằng Python và sáu lời giải tình huống. |
| [W39](CHECKLIST.md#w39) | Tiến trình, luồng và đồng bộ cơ bản | Bảng tiến trình và luồng, lịch xen kẽ gây lỗi, ví dụ được bảo vệ bằng khóa và sơ đồ kẹt cứng. |
| [W40](CHECKLIST.md#w40) | Mạng nền tảng: DNS, TCP, UDP, TLS, HTTP và kiểm tra M09 | Một sơ đồ mở trang HTTPS, mẫu HTTP được chú thích, bảng TCP và UDP, bài kiểm tra M09; không yêu cầu triển khai máy chủ công khai. |
| [W41](CHECKLIST.md#w41) | Kiểm thử, gỡ lỗi, đo hiệu năng và xử lý lỗi | Một lỗi đã tái hiện và sửa, kiểm thử chống tái phát, hai ca lỗi đầu vào, số đo trước sau và ghi chú nguyên nhân. |
| [W42](CHECKLIST.md#w42) | Thiết kế hướng đối tượng vừa đủ và chọn một mẫu phù hợp | Một ví dụ áp dụng hoặc so sánh mẫu Strategy, Factory hay Observer; sơ đồ trách nhiệm, kiểm tra hành vi và ghi chú lựa chọn cuối. |
| [W43](CHECKLIST.md#w43) | Thiết kế hệ thống ở mức nhập môn và bộ nhớ đệm LRU | Bản thiết kế một trang, bài tập LRU có năm chuỗi thao tác kiểm tra và quyết định có dùng đệm hay không; đây là phần nhập môn điều chỉnh từ mục tùy chọn. |
| [W44](CHECKLIST.md#w44) | Thiết kế Vocabulary Notebook CLI v2 và kiểm tra M10 | Đặc tả CLI v2, sơ đồ dữ liệu và phần xử lý, nguyên mẫu thêm rồi lưu và đọc thẻ, tiêu chí nghiệm thu; bài tập dự án do lộ trình bổ sung. |
| [W45](CHECKLIST.md#w45) | Ôn cấu trúc dữ liệu bằng tự nhớ lại và áp dụng vào bài mới | Bảng so sánh cấu trúc bằng trí nhớ rồi đã sửa, hai bài mới kèm kiểm tra, phân tích độ phức tạp và nhật ký lỗi. |
| [W46](CHECKLIST.md#w46) | Ôn thuật toán hỗn hợp và tự đọc tài liệu kỹ thuật | Hai bài thuật toán mới, một ghi chú đọc tài liệu với liên kết và đoạn liên quan, thử nghiệm nhỏ kiểm chứng cách dùng. |
| [W47](CHECKLIST.md#w47) | Hoàn thiện Vocabulary Notebook CLI v2 | CLI v2 chạy được với chức năng thêm, tìm, lưu và ôn theo ngày; dữ liệu mẫu tự tạo, tối thiểu tám kiểm thử có ý nghĩa, hướng dẫn tiếng Việt. |
| [W48](CHECKLIST.md#w48) | Đánh giá cuối lộ trình, trình bày dự án và chọn bước tiếp theo | Hồ sơ hoàn thành gồm bài lý thuyết, hai bài mới, minh họa dự án, bài đọc tiếng Anh, mức hỗ trợ đã dùng và bước tiếp theo; chưa tự đánh dấu trước khi có bằng chứng. |

## 6. Lộ trình tiếng Anh gắn với lập trình

| Chặng | Kỹ năng tiếng Anh trọng tâm | Đầu ra thực hành |
|---|---|---|
| W01–W08 | Nhận ra từ trong code, hiểu câu đơn, đọc thông báo lỗi | Đoạn 50–100 từ; giải thích ý chính bằng tiếng Việt; phân biệt input/output, print/return khi đã học |
| W09–W20 | Hiểu yêu cầu bài, điều kiện, so sánh và chi phí | Đoạn 80–150 từ; xác định đầu vào/đầu ra/ràng buộc; điền mẫu “This function …” |
| W21–W32 | Đọc mô tả cấu trúc/thuật toán, trình bày từng bước | Đoạn 120–200 từ; kể lại bằng tiếng Việt; tập 2–3 câu tiếng Anh có khung gợi ý |
| W33–W44 | Đọc tài liệu kỹ thuật và phân biệt thuật ngữ gần nhau | Đoạn 150–250 từ; tìm ý chính, điều kiện áp dụng, một giới hạn |
| W45–W48 | Đọc đoạn mới và giải thích dự án | Đoạn 200–300 từ; tóm tắt đúng; tự chọn tập nói/viết 3–5 câu về giải pháp |

Độ dài là mục tiêu điều chỉnh được, không phải bài thi tốc độ hay chuẩn CEFR. Tiêu chí bắt buộc ban đầu là từ vựng và đọc hiểu; tập nói/viết tăng dần qua câu mẫu và không cản việc học kỹ thuật. Không cần viết prompt bằng tiếng Anh.

Mỗi tuần checklist cho **năm thuật ngữ gợi ý**. Trong từng buổi chọn 3–5 mục cần thiết, có thể dùng lại từ cũ; không phải mỗi buổi đều thêm năm từ mới. Ban đầu giới hạn khoảng 10–15 mục mới/tuần, giảm khi chưa nhớ từ cũ. Ưu tiên từ dùng để hiểu bài hơn việc đạt số lượng từ.

Lưu mỗi mục theo: từ/cụm từ → nghĩa trong bài → câu ví dụ → bản hiểu tiếng Việt → nguồn → ngày ôn. Dùng [sổ từ vựng](learning/VOCABULARY.md); các mục mẫu chưa được tính là đã học. Có thể nghe một đoạn video chính thức ngắn có phụ đề rồi nói lại nếu muốn; không đánh dấu nghe/nói là đạt khi chưa có phần thực hành để kiểm tra.

## 7. Tiêu chí hoàn thành và quản lý tiến độ

### 7.1. Một buổi học được đánh dấu khi nào?

Đã thực hiện nhiệm vụ, lưu bài làm/ghi chú và ghi phần còn vướng. “Đã học buổi” không đồng nghĩa “đã thành thạo chủ đề”. Xem video hoặc đọc đáp án chưa đủ để đánh dấu năng lực.

### 7.2. Kỹ thuật đạt

Áp dụng tiêu chí riêng của tuần trong checklist, cộng các yêu cầu phù hợp sau:

- Giải thích đúng bằng tiếng Việt và minh họa một trường hợp.
- Với bài code: làm được nhiệm vụ chính; chạy các ca bình thường, rỗng/nhỏ nhất, trùng lặp hoặc dữ liệu không hợp lệ khi có liên quan; giải thích kết quả mong đợi.
- Làm một biến thể nhỏ không nhìn lời giải mẫu. Được tra cú pháp và tài liệu API; ghi rõ mức hỗ trợ đã dùng.
- Từ W09, với bài thuật toán: xác định đầu vào và phân tích chi phí thời gian/bộ nhớ theo giả định của bài. Với bài hệ thống: mô tả luồng xử lý và giới hạn, không ép tính Big-O.
- Đến cuối mỗi chặng bốn tuần: làm lại một bài trọng tâm sau khoảng nghỉ, không chỉ lặp đúng ví dụ ngay sau khi xem.

Nếu đã xem lời giải, buổi đó vẫn có thể tính là đã học; năng lực “đạt” cần một biến thể mới hoặc làm lại độc lập ở lần ôn sau. Trợ giảng không làm thay phần được dùng để đánh giá bạn.

### 7.3. Tiếng Anh đạt

Trong buổi S5, chọn năm từ/cụm từ trọng tâm đã học; hiểu đúng ít nhất **4/5 trong câu mới** và diễn giải đúng ý chính của đoạn đọc phù hợp chặng, không làm sai các điều kiện quan trọng. Có thể trả lời bằng tiếng Việt. Ôn lại một phần ở tuần kế tiếp; nếu quên, ghi vào hàng ôn và chưa coi là đã nhớ lâu dài.

Nếu kỹ thuật đạt nhưng tiếng Anh còn cần ôn, có thể sang tuần kỹ thuật tiếp theo và giữ mục tiếng Anh chưa đạt. Nếu thiếu kỹ thuật tiên quyết, sửa trước khi sang bài phụ thuộc. Một chặng hoàn thành cả hai mục tiêu khi bốn tuần của chặng có hai tiêu chí đạt và đã có bằng chứng ôn cuối chặng.

### 7.4. Nơi ghi và cách tính

**CHECKLIST.md là nơi ghi trạng thái chính.** Mỗi tuần có năm ô buổi học và hai ô đánh giá: kỹ thuật, tiếng Anh. Nhật ký giữ bằng chứng, quyết định rút ngắn và lỗi cần sửa. Sổ từ vựng giữ trạng thái từng từ. Không sửa các ô checklist gốc trong README để thay thế tiến độ cá nhân.

- Tiến độ kỹ thuật = số tuần có ô kỹ thuật đạt / 48.
- Tiến độ tiếng Anh = số tuần có ô tiếng Anh đạt / 48.
- Buổi đã học = số ô S1–S5 đã thực hiện / 240; đây là khối lượng thực hành, không dùng thay hai chỉ số năng lực.
- Cuối S5 cập nhật bảng tóm tắt ở đầu CHECKLIST.md, ngày cập nhật, tuần đang học và buổi tiếp theo. Các số là ghi thủ công, không tự đồng bộ.

## 8. Ôn tập, điều chỉnh và quay lại sau khi nghỉ

Lịch ôn gợi ý: sau 1, 3, 7, 14 và 30 ngày tính từ ngày thực học. Đây là quy ước thực hành ban đầu, có thể đổi; lịch nhắc chỉ được ghi trong sổ, chưa tạo thông báo tự động. Với mỗi lần ôn, tự nhớ trước rồi mở đáp án; từ hoặc bài còn quên được đưa lại sớm hơn.

Sau W02, dùng số giờ thật và số nhiệm vụ hoàn thành để điều chỉnh. Nếu liên tục thiếu thời gian, chia một tuần học thành hai tuần lịch; giảm bài mở rộng, giữ bài trọng tâm và ôn. Không dồn toàn bộ bài chưa học thành một tuần bù quá tải.

Sau mỗi chặng, ghi ba điều: đã tự làm được gì; đang vướng gì; cần đổi lịch/tài liệu nào. Khi nghỉ lâu, bắt đầu từ nhật ký gần nhất, làm một bài nhớ lại và một bài nhỏ; chỉ học lại phần quên. Giữ một tuần chính đang học và một hàng ôn, tránh mở quá nhiều chủ đề cùng lúc.

## 9. Dự án xuyên suốt: Vocabulary Notebook

Một chương trình quản lý từ vựng chuyên ngành chạy bằng dòng lệnh — **CLI, command-line interface**, nghĩa là nhập lệnh và đọc kết quả dạng chữ. Dự án được chọn để việc học code hỗ trợ trực tiếp việc học tiếng Anh.

| Mốc | Phạm vi | Cách kiểm tra |
|---|---|---|
| W08 — v1 | Thêm mục từ, liệt kê, tìm chính xác, lưu/đọc JSON | Dữ liệu mẫu tự tạo; trường hợp chưa có từ, từ trùng, khởi động lại |
| W16 — áp dụng chọn lọc | Giải thích dùng list/dict; so sánh tìm tuyến tính và tra cứu | Kết quả đúng; giải thích chi phí kỳ vọng và giới hạn |
| W24 — bài tập độc lập | Trie để tìm tiền tố trên tập từ nhỏ | Phân biệt khớp cả từ với khớp tiền tố; tiền tố không có kết quả |
| W44 — thiết kế v2 | Xác định yêu cầu, mô hình dữ liệu, luồng thêm/tìm/ôn, chạy một luồng mẫu | Đầu vào/đầu ra rõ; ghi lựa chọn cấu trúc và các trường hợp lỗi |
| W47–W48 — hoàn thiện v2 | Lịch ôn theo ngày, tìm từ, lưu trạng thái, xử lý lỗi, tài liệu sử dụng | Ca ngày đến hạn/chưa đến hạn, dữ liệu rỗng, tệp lỗi, khởi động lại; demo từ đầu |

V1 là bản nhỏ để học, có thể tách thành nhiều tuần nếu mới bắt đầu. Các cấu trúc tự cài phục vụ hiểu nguyên lý; dự án cuối có thể dùng cấu trúc/thư viện chuẩn sau khi giải thích lý do. Không bắt buộc ghép mọi thuật toán đã học vào sản phẩm.

## 10. Đối chiếu với repo và phần mở rộng

| Nhóm trong Coding Interview University | Tuần trong kế hoạch | Độ sâu được chọn |
|---|---|---|
| Study plan, chọn ngôn ngữ, luyện bài | W01–W08 và xuyên suốt | Thêm nền tảng Python; chọn tài liệu vừa sức |
| Big-O; recursion; binary search; bitwise | W09–W12, W29–W32 | Cài đặt/mô phỏng phần cơ bản, ôn lại trong bài tập |
| Arrays, linked lists, stack, queue, hash table | W13–W16 | Tự cài bản học tập; mảng dùng bộ đệm mô phỏng, bảng băm dùng chaining |
| Sorting | W17–W18, W23 | Selection/insertion; merge/quick; heap; so sánh tính chất |
| Trees, BST, heap, tries | W21–W24 | Thao tác chính và bài ứng dụng; cây cân bằng ở mức ý tưởng |
| Graphs | W25–W28 | BFS/DFS, liên thông, chu trình, topo, Dijkstra, Prim; Bellman–Ford ở mức ý tưởng |
| Recursion, DP, combinatorics, probability, NP | W29–W34 | Bài nhỏ, mô hình, điều kiện áp dụng và giới hạn |
| String searching, Unicode | W35; ôn W36 | Tìm trực tiếp; ý tưởng KMP; xử lý văn bản có dấu |
| Computer execution, caches, processes/threads, networking | W37–W40, W43 | Mức giải thích và mô phỏng; có bài cache ứng dụng |
| Testing, design patterns | W07, W41–W42 | Kiểm thử và dùng mẫu thiết kế phù hợp; không học thuộc toàn bộ danh sách |
| Final review | W36, W45–W48 | Bài mới, ôn cách quãng, dự án và đọc hiểu |
| System design — vốn là mục tùy chọn của repo | W43–W44 | Chọn phần nhập môn phục vụ hiểu hệ thống; thiết kế quy mô lớn để sau |
| Getting the job | X01–X04 bên dưới | Tùy chọn khi mục tiêu tuyển dụng rõ hơn |

**Phạm vi hoàn thành:** 48 tuần là lộ trình cá nhân chọn lọc, không phải tích hết mọi video, sách hay bài triển khai trong CIU. Các mẫu two pointers, sliding window, bài Python nền tảng, tiếng Anh và dự án là phần bổ sung của kế hoạch. Tài liệu gốc và bản dịch vẫn là kho tham chiếu; khi giải thích khác nhau, đối chiếu định nghĩa và thử ví dụ.

### Phần tiếp theo tùy mục tiêu — không tính vào 48 tuần

| Mã | Thời lượng mẫu | Nội dung | Bằng chứng |
|---|---:|---|---|
| X01 | 1 tuần học | Đọc mô tả việc làm, chọn vai trò, rà soát điểm thiếu | Một bản đối chiếu yêu cầu với bài làm hiện có |
| X02 | 1 tuần học | CV và mô tả dự án Việt–Anh | Bản giới thiệu trung thực, có minh chứng |
| X03 | 1 tuần học | Hai buổi phỏng vấn mô phỏng kỹ thuật | Bài giải, cách giải thích và phản hồi cụ thể |
| X04 | 1 tuần học | Sửa điểm yếu, luyện hỏi làm rõ và câu hỏi cho người phỏng vấn | Một lần làm lại sau phản hồi |

Nhánh đào sâu chọn sau: con trỏ/quản lý bộ nhớ bằng C; linear probing và xóa trong bảng băm; cây tự cân bằng; strongly connected components (thành phần liên thông mạnh); đồ thị hai phía; union-find; triển khai KMP/Rabin–Karp; các mẫu thiết kế còn lại; hệ điều hành và hệ phân tán sâu hơn. SQL/cơ sở dữ liệu, web và bot ứng dụng có thể thành lộ trình riêng khi cần; chúng chưa phải sản phẩm đầu ra của kế hoạch này.

## 11. Tài liệu và ghi nhận nguồn

1. **Nguồn trục chính:** [README Coding Interview University trong repo này](README.md), bản được kiểm tra tại commit [78c0942](https://github.com/dvha85/coding-interview-university/commit/78c09424a792de42cb73d4b8a6090112652bfd06); tác giả John Washam và cộng đồng [repo gốc](https://github.com/jwasham/coding-interview-university). Kế hoạch đã sắp xếp lại và bổ sung nội dung cá nhân như mô tả ở trên; xem [giấy phép của repo](LICENSE.txt).
2. **Cầu nối ngôn ngữ:** [Bản dịch tiếng Việt](translations/README-vi.md). Đọc đoạn tiếng Anh theo chủ đề trước hoặc sau lời giải thích tiếng Việt; dùng bản dịch để đối chiếu, không bắt đọc toàn bộ song song.
3. **Python:** [Tutorial](https://docs.python.org/3/tutorial/), [Glossary](https://docs.python.org/3/glossary.html), [unittest](https://docs.python.org/3/library/unittest.html). Chọn đúng mục cần cho bài; phần giới thiệu mới sẽ giải thích thuật ngữ trước.
4. **Thuật toán:** [MIT 6.006 — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/). Dùng từng bài giảng/ghi chú phù hợp W09 trở đi; đây là khóa đại học, không bắt người mới học hết ngay. Ví dụ code cũ cần được chuyển và kiểm tra trên Python 3 khi sử dụng.
5. **Kho tham khảo ngôn ngữ:** [Programming Language Resources](programming-language-resources.md). Liên kết trong repo là gợi ý lựa chọn, không phải tất cả đều bắt buộc hoặc đều đã được kiểm tra khả dụng.

Các đoạn tiếng Anh, bài tập và tiêu chí trong phần học cá nhân do trợ giảng tự soạn, trừ khi ghi nguồn cụ thể. Khi một nguồn cũ không mở được hoặc cú pháp đã đổi, chọn tài liệu chính thức tương đương và ghi nguồn thay trong nhật ký.
