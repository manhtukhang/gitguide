Git - Hướng dẫn cơ bản
==
**Lời nói đầu**    
Bài viết này là kinh nghiệm, quan điểm cá nhân của mình, nếu bạn thấy không thích có thể không cần đọc tiếp. Còn nếu bạn quan tâm và thấy có thiếu sót (chắc chắn là có vì mình không giỏi viết lách này nọ) thì hãy góp ý để mình bổ sung, hoàn thiện.    
Sau khi đọc xong bài này bạn sẽ biết cách làm sao để đóng góp.  


# Mục lục
- [Giới thiệu](#giới-thiệu)
    - [Git là gì?](#git-là-gì)
    - [Tại sao lại sử dụng Git?](#tại-sao-lại-sử-dụng-git)
- [Các tính năng của Git](#các-tính-năng-của-git)
- [Cài đặt Git](#cài-đặt-git)
    - [Cài đặt](#cài-đặt)
    - [Thiết lập cơ bản](#thiết-lập-cơ-bản)
- [Làm việc với Git](#làm-việc-với-git)
- [Các quy tắc chung](#các-quy-tắc-chung)



# Giới thiệu
## Git là gì?
Git là **Hệ Thống Quản Lý Phiên Bản Phân Tán - Distributed Version Control Systems (DVCSs)**  
Có thể bạn vẫn đang mù mờ về nó, không sao cứ đọc tiếp

## Tại sao lại sử dụng Git?
Đầu tiên bạn hãy xem qua các tình huống sau:

- *Đã bao giờ bạn rơi vào cảnh đang làm bài tập và phải tạm dừng vì quá trễ, sáng hôm sau thức dậy bạn không biết phải tiếp tục từ đâu?*
- *Đã bao giờ bạn sửa 1 đoạn code nhưng 2 ngày sau đó bạn nhận ra mình đã làm cho nó sai hơn và bạn muốn quay về 2 ngày trước?*
- *Bạn làm việc theo nhóm, mỗi người làm 1 kiểu, đôi khi bạn làm lại việc của người khác, vậy làm sao để tránh việc đó*

Tất nhiên bạn đã có cách của riêng mình, chẳng hạn như sau:

- *Tôi đã ghi lại những thứ quan trọng vào sổ tay. Tôi có trí nhớ tốt!*  
    Đó chỉ là công việc nhỏ, nếu bạn phải nhớ và ghi chép nhiều thứ thì có chắc là bạn sẽ không sai xót chứ?
- *Tôi đã sao lưu dự phòng rồi.*  
    Điều đó rất tốt nhưng sau mỗi thay đổi bạn phải sao lưu 1 bản thì đến lúc nào đó bạn lại lao vào mớ hỗn độn do chính bạn tạo ra  
- *Chúng tôi gặp nhau và cùng làm.*  
    Nghĩa là các bạn phải gặp nhau, và nếu có ai đó phải về quê chẳng hạn thì sao?  

Và Git ra đời để giải quyết các vấn đề trên, không những vậy còn làm rất tốt

# Các tính năng của Git
- **Lưu lại mọi thứ** nghĩa là bạn luôn có thể quay ngược lịch sử và sửa sai với Git  
    _Ví dụ:_ bạn lỡ tay xóa 1 đoạn code và hôm sau mới sực nhớ ra, lúc đó đã muộn, có thể bạn phải làm lại từ đầu. Nhưng với Git, bạn luôn có thể quay lại bất kì thời điêm nào trước đó.
- **Mỗi thay đổi đều được ghi chú** nghĩa là Git giúp bạn có thể biết chính xác mình đã làm gì trước đó   
    _Ví dụ:_ bạn thêm vào 1 tệp tin vào dự án nhưng sau đó lại không nhớ tại sao mình làm vậy. Git giúp bạn làm tốt điều này.
- **Làm việc nhóm hiệu quả** Git giúp mọi người trong nhóm làm tốt phần việc của họ, tránh chồng chéo  
    _Ví dụ:_ bạn làm việc chung với nhiều người trên cùng 1 dự án, cả 2 người cùng sửa 1 tập tin, nhưng mỗi người làm 1 kiểu. Git giúp mọi người không bị lệch pha so với người khác.  
- **Thử nghiệm tính năng mà không sợ làm hỏng mọi thứ**
    _Ví dụ:_ bạn viết xong 1 chương trình nhưng muốn thêm vào một số tính năng. Git sẽ giúp bạn chuyển sang 1 nhánh để bạn thoải mái sáng tạo, sau khi hoàn tất, bạn chỉ việc gộp vào với những thứ khác mà không sợ phá hỏng mọi thứ có sẵn  
- **Làm việc khi không có mạng Internet** nếu ai đã từng làm việc với SubVersion hay SourceForge sẽ biết, khi không có mạng, bạn sẽ không thể liên lạc với máy chủ đồng nghĩa với việc không thể làm được gì. Nhưng Git thì khác, trên máy bạn là một kho riêng và đầy đủ, bạn chỉ kết nối đến máy chủ khi cần chia sẻ công việc của mình.  
Và còn nhiều hơn thế nữa các bạn có thể tham khảo thêm trên mạng

# Cài đặt Git

## Cài đặt

## Thiết lập cơ bản

# Làm việc với Git

# Các quy tắc chung
- Luôn `commit` với mỗi thay đổi, tránh `commit -a`  
- Thông điệp `commit` phải ngắn gọn (không quá 72 kí tự), rõ ràng (nói rõ thay đổi) và phải là **Tiếng Anh** (vì không phải lúc nào Tiếng Việt có dấu cũng được hiển thị đúng còn Tiếng Việt không dấu có thể gây hiểu nhầm)  
- Tuyệt đối không được `rebase` hoặc `commit --amend` khi bạn đã đẩy nhánh đó lên kho dùng chung vì lúc đó bạn sẽ làm mọi thứ rối tung lên, ảnh hưởng đến người khác đang làm chung với bạn  
- Luôn `pull` trước khi `push` để đảm bảo bạn không "phát minh lại bánh xe"
- Khi muốn thêm mới hoặc thử nghiệm thứ gì, bạn nên `checkout` ra nhánh mới, sau khi mọi thứ hoàn thiện thì mới `merge`
- Nếu bạn muốn người khác thử nghiệm giúp bạn, hãy `push` lên nhánh mới do bạn tạo ra, không phải là nhánh ổn định như *master* hoặc *release*
- Bạn phải đảm bảo thay đổi do mình tạo ra trên nhánh riêng có thể `auto merge` vào nhánh chính