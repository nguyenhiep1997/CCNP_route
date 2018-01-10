# CCNP route 

----------------------------------
 
 - giới hạn trách nhiệm và từ chối bảo hành : Nhà xuất bản đã nỗ lực hết mình để soạn cuốn sách này, và thông tin được cung cấp ở đây được như bạn thấy. René Molenaar không đại diện hay đảm bảo về tính chính xác hoặc đầy đủ của nội dung của cuốn sách này và từ chối bất kỳ sự bảo đảm ngụ ý nào về khả năng bán hoặc tính phù hợp cho bất kỳ mục đích cụ thể nào và sẽ không bao giờ chịu trách nhiệm về bất kỳ tổn thất lợi nhuận hoặc thiệt hại thương mại nào khác , bao gồm nhưng không giới hạn ở các thiệt hại đặc biệt, ngẫu nhiên, do hậu quả hoặc các thiệt hại khác.

 - Thương hiệu: Cuốn sách này xác định tên sản phẩm và dịch vụ được biết là nhãn hiệu, nhãn hiệu đã đăng ký, hoặc nhãn hiệu dịch vụ của chủ sở hữu tương ứng. Chúng được sử dụng trong toàn bộ cuốn sách này chỉ trong thời gian xuất bản. Ngoài ra, các điều khoản nghi ngờ là thương hiệu, nhãn hiệu đã đăng ký, hoặc nhãn hiệu dịch vụ đã được xác định riêng , mặc dù René Molenaar không thể chứng thực tính chính xác của thông tin này. Việc sử dụng thuật ngữ trong cuốn sách này không được coi là ảnh hưởng đến hiệu lực của bất kỳ nhãn hiệu, nhãn hiệu đã đăng ký hoặc nhãn hiệu dịch vụ nào. René Molenaar không liên quan đến bất kỳ sản phẩm hoặc nhà cung cấp nào được đề cập trong cuốn sách này.

## giới thiệu 

 - Một trong những điều tôi làm trong cuộc đời là làm việc với tư cách là Người hướng dẫn Hệ thống Có Chứng nhận của Cisco (CCSI) và sau khi dạy CCNA / CCNP trong vài năm, tôi đã học được những chủ đề mà mọi người thấy khó hiểu. Đây là lý do tôi tạo ra http://gns3vault.com nơi tôi cung cấp miễn phí các phòng thí nghiệm và video của Cisco để giúp mọi người học mạng. Vấn đề với mạng là bạn cần biết mình đang làm gì trước khi bạn có thể cấu hình bất cứ thứ gì. Ngay cả khi bạn có tất cả các lệnh bạn vẫn cần phải hiểu những gì và tại sao bạn gõ lệnh này. Tôi đã tạo ra cuốn sách này để cung cấp cho bạn một hướng dẫn nhỏ gọn cung cấp cho bạn câu trả lời cho những gì và tại sao để giúp bạn nắm vững kỳ thi ROUTE CCNP. Tôi đã cố gắng để đặt tất cả các từ khóa quan trọng in đậm. Nếu bạn thấy một thuật ngữ hoặc khái niệm in đậm nó là một cái gì đó bạn nên nhớ / viết ra và chắc chắn rằng bạn hiểu nó kể từ khi kiến thức cốt lõi của nó cho CCNP của bạn!

 - Một điều cuối cùng trước khi chúng tôi bắt đầu. Khi tôi dạy tôi luôn chỉ bảo cho sinh viên tạo ra những bản đồ tư duy (midmap) thay vì chú thích . Ghi chú chỉ là danh sách với thông tin ngẫu nhiên trong khi các bản đồ tư duy thể hiện mối quan hệ giữa các mục khác nhau. Nếu bạn đang đọc cuốn sách này trên máy tính của bạn, tôi đề nghị bạn tải xuống "Xmind" mà bạn có thể tải miễn phí tại đây: [xmind](http://xmind.net) .Nếu bạn là người mới dùng mindmapping, hãy kiểm tra "Phụ lục A - Làm thế nào để tạo các bản ghi nhớ" ở cuối cuốn sách này, nơi tôi chỉ cho bạn cách tôi làm điều đó.

 - Tôi cũng rất khuyên bạn nên theo tôi cùng khi tôi đang trình diễn các ví dụ cấu hình. Khởi động GNS3 và cấu hình các ví dụ tôi tự hiển thị cho bạn. Bạn sẽ học được nhiều hơn bằng cách tích cực làm việc trên các bộ định tuyến so với đọc chỉ thụ động.Thưởng thức đọc cuốn sách của tôi và chúc bạn may mắn nhận chứng chỉ CCNP ROUTE

 - nếu bạn có bất kỳ câu hỏi nào về cuốn sách này hãy liên hệ với tôi : 
 [E-mail:](info@gns3vault.com)
 [Website:](gns3vault.com)
 [Facebook:](facebook.com/gns3vault)
 [Twitter:](twitter.com/gns3vault)
 [Youtube:](youtube.com/gns3vault)


 Index
Introduction ............................................................................................................ 3
[1. Introduction to EIGRP ........................................................................................... 5](#1)
[2. EIGRP Packets and Metrics .................................................................................. 15](#2)
[3. EIGRP Summarization ......................................................................................... 35](#3)
[4. EIGRP over Frame-Relay ..................................................................................... 45](#4)
[5. EIGRP Authentication .......................................................................................... 67](#5)
[6. EIGRP Advanced Features ................................................................................... 70](#6)
[7. Introduction to OSPF .......................................................................................... 87](#7)
[8. OSPF Packets and Neighbor discovery ................................................................... 98](#8)
[9. OSPF Network Types..........................................................................................105](#9)
[10. OSPF LSA Types ..............................................................................................123](#10)
[11. OSPF Summarization .......................................................................................133](#11)
[12. OSPF Special Area Types ..................................................................................138](#12)
[13. OSPF Authentication ........................................................................................144](#13)
[14. OSPF Virtual Links ...........................................................................................148](#14)
[15. Route Selection ...............................................................................................155](#15)
[16. Route Manipulation ..........................................................................................175](#16)
[17. Redistribution ................................................................................................. 186](#17)
[18. Introduction to BGP (Border Gateway Protocol) ....................................................212](#18)
[19. BGP Attributes and Path selection ......................................................................244](#19)
[20. Introduction to IPv6 .........................................................................................263](#20)
[21. IPv6 Routing Protocols .....................................................................................292](#21)
[22. IPv6 Migration & Tunneling ...............................................................................313](#22)
[23. Remote Site Connectivity ..................................................................................325](#23)
[24. Router Security ...............................................................................................339](#24)
[25. Final Thoughts ................................................................................................356](#25)
[Appendix A – How to create mindmaps ....................................................................357](#0)

<a name=1></a>

## 1. giới thiệu về EIGRP 

 - Giao thức định tuyến đầu tiên chúng ta sẽ xem xét được gọi là EIGRP (Enhanced Interior Gateway Routing Protocol). EIGRP được tạo ra bởi Cisco có nghĩa là bạn chỉ có thể chạy nó trên phần cứng của Cisco. Nếu bạn muốn định tuyến với các thiết bị từ các nhà cung cấp khác nhau (như Juniper), bạn sẽ phải tìm kiếm một giao thức định tuyến khác.

 - Trong chương này tôi sẽ giới thiệu cho bạn về EIGRP. chúng ta sẽ thấy cách hoạt động và cách EIGRP khác so với OSPF. Hầu hết các thông tin trong chương này là một bài đánh giá của EIGRP trên cấp độ CCNA vì vậy nếu bạn có tất cả mọi thứ vẫn còn tươi mới trong tâm trí bạn có thể muốn bỏ qua chương. Hãy để tôi bắt đầu bằng cách cung cấp cho bạn một cái nhìn tổng quan:
 <ul>
 <li>Giao thức định tuyến đường cao tốc hoặc Giao thức định tuyến lai.</li>
 <li>Multicast hoặc unicast được sử dụng để trao đổi thông tin.</li>
 <li>Nhiều giao thức lớp mạng được hỗ trợ.</li>
 <li>100% không có vòng lặp.</li>
 </ul>

 - Tại sao chúng ta gọi EIGRP là một vector khoảng cách cao hoặc giao thức định tuyến lai? Nếu bạn học CCNA bạn đã thấy RIP. RIP là một giao thức định tuyến vector khoảng cách thật và rất đơn giản:
 <ul>
 <li> không thiết lập láng giềng </li>
 <li>cập nhật định kỳ </li>
 <li>dễ bị loop </li>
 <li>metric đơn giản (hop count)</li>
 </ul>

 - Cisco đã bổ sung một số tính năng từ các giao thức định tuyến link - state cho EIGRP làm cho nó trở nên tiên tiến hơn một giao thức định tuyến vector khoảng cách gốc như RIP. Đây là lý do tại sao (có thể là bộ phận tiếp thị) gọi EIGRP là một distance vector nâng cao hoặc giao thức định tuyến lai. 

 - EIGRP không sử dụng các gói tin broadcast để gửi thông tin đến các hàng xóm khác nhưng sẽ sử dụng các nhóm multicast hoặc unicast. Ngoài IPv4 bạn cũng có thể sử dụng EIGRP để định tuyến IPv6 hoặc thậm chí một số giao thức lớp mạng cũ hơn như IPX hoặc AppleTalk. Cuối cùng nhưng không kém phần quan trọng ... EIGRP là 100% vòng lặp miễn phí và tôi sẽ cho bạn thấy lý do tại sao điều này là đúng.
 
 ![](https://i.imgur.com/DbKiFHW.png)

 - EIGRP chạy trực tiếp trên đầu trang của tiêu đề IP. Nếu bạn nhìn vào bức tranh ở trên, bạn thấy chúng ta có một frame header (ví dụ như frame Ethernet), header IP (chúng ta đang sử dụng IPv4) và bên trong gói IP bạn sẽ tìm thấy EIGRP. EIGRP có số giao thức riêng của nó là 88. Các số giao thức khác mà bạn quen thuộc là TCP (6) và UDP (17).

  ![](https://i.imgur.com/PjJg2w0.png)

 -Liệt kê tất cả các hàng xóm kết nối trực tiếp:
 -router tiếp theo
 -Giao diện

 - Liệt kê tất cả các tuyến đường đã học từ tất cả các hàng xóm của EIGRP:
 - Điểm đến
 -  Số liệu

 - Các tuyến đường tốt nhất từ bảng topology EIGRP sẽ được sao chép vào bảng định tuyến.

 - Các bộ định tuyến EIGRP sẽ bắt đầu gửi gói tin hello tới các bộ định tuyến khác giống như OSPF. nếu bạn gửi các gói tin hello và bạn nhận được chúng, bạn sẽ trở thành hàng xóm. Các hàng xóm của EIGRP sẽ trao đổi thông tin định tuyến và sẽ được lưu trong bảng topology. Đường dẫn tốt nhất từ bảng tô pô sẽ được sao chép vào bảng định tuyến. 

 - việc Chọn đường đi tốt nhất với EIGRP hoạt động khác một chút so với các giao thức định tuyến khác, vậy hãy xem nó đang hoạt động:

 ![](https://i.imgur.com/CkCvbBw.png)

 - Chúng ta có ba router có tên là KingKong, Ann và Carl. Chúng ta sẽ tính toán con đường tốt nhất đến đích đến phía sau router Carl. EIGRP sử dụng một bộ số liệu phong phú bao gồm **băng thông, độ trễ, tải và độ tin cậy** mà chúng tôi sẽ trình bày sau. Các giá trị này sẽ được đưa vào công thức và mỗi liên kết sẽ được nhận một số liệu. Các số liệu này càng thấp càng tốt. Trong hình trên, tôi đã gán một số giá trị trên các interface, nếu bạn nhìn vào một bộ định tuyến EIGRP thực, bạn sẽ thấy các con số rất cao và hơi gây phiền nhiễu khi làm việc

 - Router Carl sẽ quảng cáo đến bộ định tuyến Ann của nó về phía đích. Về cơ bản router Carl đang nói với router Ann: "cost của tôi là 5 để đến đó". Đây được gọi là **advertised distance (AD)**.

 ![](https://i.imgur.com/onj3rqh.png)

 - Router Ann có một bảng tô pô và trong bảng topology này, nó sẽ lưu lại số liệu này,
khoảng cách được quảng cáo để đến đích này là 5.

![](https://i.imgur.com/ZDpkZKI.png)

 - Chúng ta chưa thực hiện đi được vì router Ann chưa có gì để lưu trong bảng tô pô của nó. Chúng tôi biết AD là 5 vì đây là những gì router Carl nói với chúng tôi. Chúng ta cũng biết được số liệu của liên kết giữa router Ann và router Carl vì đây là kết nối trực tiếp. Router Ann bây giờ biết số liệu cho tổng số đường dẫn đến đích, tổng số đường dẫn được gọi là khoảng cách khả thi **(feasible distance)** và nó sẽ được lưu trong bảng tô pô.
 ![](https://i.imgur.com/FWxLDyn.png)

 - Bây giờ bạn đã học được hai khái niệm quan trọng của EIGRP. AD là hàng xóm của bạn cho bạn biết khoảng cách từ anh ta để đạt đến điểm đến và feasible distance (FD) là khoảng cách tổng thể của bạn để đến đích.

![](https://i.imgur.com/7XTyppC.png)

 - Chúng ta vẫn chưa thực hiện đi được vì router KingKong cũng đang chạy EIGRP. Router Ann đang gửi khoảng cách khả thi(feasible distance)  đối với router KingKong là 15. Router KingKong sẽ lưu thông tin này trong bảng cấu trúc mạng như khoảng cách được quảng cáo(AD) . Router Ann là "nói" với router KingKong khoảng cách là 15. 
 ![](https://i.imgur.com/7ccUvoq.png)

 - Router KingKong giờ đã biết đích đến của Router Ann là bao xa và kể từ khi chúng ta biết được số liệu cho liên kết giữa router KingKong và Ann nó cũng có thể tính tổng khoảng cách được gọi là khoảng cách khả thi(feasible distance) . Thông tin này được lưu trong bảng tô pô. Bạn có theo tôi cho đến nay? Hãy để tôi mô tả các thuật ngữ này một lần nữa nhưng trong tiếng anh đơn giản:
 <ul>
 <li>Advertised distance: khoảng cách từ bạn đến hàng xóm là bao xa.</li>
 <li>Feasible distance: tổng khoảng cách từ bạn đến đích.</li>
 </ul>

 - Con đường tốt nhất đến đích được gọi là **successor!**

 - successor sẽ được sao chép từ bảng tô pô đến bảng định tuyến

 - Với EIGRP tuy nhiên có thể có một đường dẫn dự phòng mà chúng ta gọi là feasible successor. Làm thế nào để chúng ta biết chúng ta có một feasible successor không? Hãy cùng tìm hiểu:

![](https://i.imgur.com/F5Gsg9i.png)

 - Trong ví dụ trên chúng ta có một vài bộ định tuyến chạy EIGRP; chúng ta đang ngồi trên router không có tên ở bên trái và muốn biết hai điều:
 <ul>
 <li> Đường dẫn nào là successor (con đường tốt nhất)?</li>
 <li>Chúng ta có những feasible successors không? (đường dẫn dự phòng)</li>
 </ul>

 - Hãy điền vào bảng dưới đây để tìm hiểu:

 ![](https://i.imgur.com/EhGZntM.png)

 - Nếu bạn muốn thử các kỹ năng EIGRP đã học mới, hãy tự mình điền vào advertised và feasible distance của mình trong bảng bên trên.
 - Router KingKong nói với chúng ta khoảng cách từ nó đến đích đến là 10 , router Ann nói với chúng ta khoảng cách từ nó đến đích là 5 và router Carl nói với chúng ta khoảng cách từ nó đến đích là 9 . Bây giờ chúng ta có thể điền vào phần advertised distance của bảng:

![](https://i.imgur.com/JWjrMsP.png)
 
 - Vì chúng ta biết liên kết trực tiếp của chúng, chúng ta có thể cộng vào khoảng cách được quảng cáo (AD) và chúng tôi sẽ có khoảng cách khả thi (FD)

 ![](https://i.imgur.com/RYiLKt2.png)
 - Con đường với khoảng cách khả thi thấp nhất sẽ là successor (router Ann) nên bây giờ chúng ta đã trả lời câu hỏi đầu tiên.
 ![](https://i.imgur.com/9JkrzDw.png)

 - Bạn sẽ tìm thấy successor bảng định tuyến. Để trả lời câu hỏi thứ hai "chúng ta có một feasible successor (đường dẫn dự phòng) không?" Chúng ta cần học một công thức khác: **AD của đường feasible successor phải < FD của đường chính **

 - Đây là khi tôi nhận được để nhìn thấy đôi mắt bằng kính và sinh viên rảng rịch nên chúng ta hãy làm nó bằng tiếng Anh đơn giản hơn một lần nữa: Một router có thể trở thành một đường dẫn sao lưu nếu anh ta đến gần đích hơn tổng khoảng cách của con đường tốt nhất của bạn. Tôi nghĩ rằng âm thanh tốt hơn một chút? Hãy thử nó và xem nếu router KingKong hoặc router Carl phù hợp như một đường dẫn sao lưu: AD của bộ định tuyến KingKong là 10 tương đương với FD của bộ định tuyến Ann cũng bằng 10. Nó phải thấp hơn ... bằng là không đủ , nên router KingKong sẽ KHÔNG trở thành  feasible successor. AD của router Carl là 9 thấp hơn FD của router Ann là 10. Router Carl sẽ là  feasible successor và được sử dụng như một đường dẫn sao lưu!

 ![](https://i.imgur.com/626BpwP.png)

 - Tuyệt vời vì vậy router Ann là successor và router của chúng tôi Carl là một feasible successor. Bạn sẽ tìm thấy cả hai mục nhập trong topo EIGRP nhưng bạn sẽ chỉ tìm thấysuccessor trong bảng định tuyến. Nếu bạn bị mấtsuccessor vì một lỗi liên kết EIGRP sẽ sao chép / dán feasible successor trong bảng định tuyến. Đây là những gì làm cho EIGRP một giao thức định tuyến FAST ... nhưng chỉ khi bạn có feasible successor trong bảng tô pô.

 - Bây giờ nhìn vào cuối với feasible distance của router Carl và router KingKong ... những gì bạn nhìn thấy? Các số liệu cho router Carl là đến đích tồi tệ hơn một chút so với router KingKong. Liệu điều này có ý nghĩa gì? có phải Các kỹ sư của Cisco EIGRP đã tạo ra một sai lầm kinh khủng ở đây bằng cách sử dụng đường dẫn sao lưu không tối ưu không?

 - Không, đây là cách hoàn hảo nhất. Hãy ghi nhớ EIGRP ở cốt lõi là một giao thức vector khoảng cách. Nó không biết mạng lưới hoàn chỉnh như thế nào ... nó không phải là một giao thức định tuyến kết nối trạng thái như OSPF để mà có một bản đồ hoàn chỉnh của mạng. Các giao thức định tuyến vector khoảng cách chỉ biết được cách nào để đi (vector) và cách xa đích đến (khoảng cách). Tôi sẽ cho bạn thấy một cách chính xác tại sao EIGRP hoạt động như thế này.

 - EIGRP có một thủ thuật khác trong cấu tạo của nó. RIP và OSPF đều có thể cân bằng tải nhưng đường đi phải có cost bằng nhau.  EIGRP có thể làm điều gì đó tuyệt hơn ... cân bằng tải trên những đường không bằng nhau về cost! Thậm chí nó sẽ chia sẻ lưu lượng theo tỷ lệ, nếu bạn có một feasible successor có feasible distance gấp 5 lần so với lưu lượng truy cập kế tiếp sẽ được chia sẻ theo cách 5: 1.

![](https://i.imgur.com/I8BEm7S.png)

![](https://i.imgur.com/Jgm18PJ.png)

- Đây là ví dụ đầu tiên của chúng tôi, nơi chúng tôi tìm được n successor và feasible successor . Nếu bạn nhìn vào bảng định tuyến, bạn sẽ chỉ tìm thấy successor ở đó. Bây giờ chúng ta sẽ thay đổi mọi thứ vì vậy chúng ta sẽ thấy sự kế thừa khả thi trong bảng định tuyến để nó sẽ cân bằng tải

 - Bạn có thể làm điều này bằng cách sử dụng lệnh variance. Lệnh variance hoạt động như một hệ số nhân: 
 <ul>
 <li>successor có FD ( đường đến đích) là 10</li>
 <li>feasible successor có FD ( đường đến đích) là 109 </li>
 </ul>

 - để có thể cân bằng tải trên đường dự phòng (feasible successor) chúng ta cần có FD của đường dự phòng phải nhỏ hơn FD của đường chính sau khi nhân với variance .
 - Nếu chúng ta đặt variance ở mức 2, đây là những gì chúng ta nhận được:
 <ul>
 <li>FD của đường chính ( successor) là 10x2 = 20 </li>
 <li>109 là lớn hơn so với 20 nên chúng ta không thể load balancing</li>
 </ul>

 - nếu chúng ta đặt varinace là 5 thì chúng ta nhận được:
 <ul>
 <li>FD của đường chính bây giờ là 10x5=50 </li>
 <li>FD của đường phụ là 109 vẫn là lớn hơn so với FD của đường chính nên vẫn chưa có cân bằng tải ( load balancing)</li>
 </ul>
 - bây giờ chúng ta thử đặt variance là 11 để xem sao :
 <ul>
 <li>FD của successor là 10x11=110 </li>
 <li>109 thấp hơn 110 vì vậy bây giờ chúng ta sẽ đặt feasible successor trong bảng định tuyến và bắt đầu cân bằng tải!</li>
 </ul>

 - Có phải chúng ta sẽ sử dụng tuyến đường thông qua router KingKong? Không, chúng ta sẽ không làm thế vì nó không phải là một người kế thừa khả thi (feasible successor)!

 - Công thức mà bạn vừa thấy để xác định những người kế thừa khả thi (feasible successor) EIGRP là làm thế nào EIGRP có thể đảm bảo rằng đường dẫn sao lưu là 100% không lặp! Tôi biết điều này rất khó nắm bắt bằng cách đọc văn bản vì vậy chúng ta hãy làm một ví dụ khác
 ![](https://i.imgur.com/IveHXqc.png)

 - Hãy nhớ rằng EIGRP là bởi một giao thức định tuyến vector khoảng cách, chúng ta thấy topo nhưng EIGRP thì không!
 - Chúng tôi đang xem xét bảng topology EIGRP của router Hearts và chúng tôi muốn tiếp cận điểm đến phía sau router Spade, hãy điền vào bảng (hãy thử nó nếu bạn muốn có một bài tập tốt):

 ![](https://i.imgur.com/r4GeWmq.png)

 - 1. Router Spade sẽ quảng cáo mạng đích đến router Hearts
 - 2. Router Hearts sẽ quảng cáo mạng tới router Clubs và Diamond.
 - 3. Router Clubs sẽ quảng cáo mạng tới router Diamond
 - 4. Router Diamond sẽ quảng cáo mạng tới router Clubs.
 - 5. Router Clubs sẽ quảng cáo mạng này trở lại router Hearts.
 - 6. Router Diamond sẽ quảng cáo mạng này trở lại router Hearts.

 ![](https://i.imgur.com/zX6sXbX.png)

 - Ở đây chúng tôi có advertised distance; những người hàng xóm của chúng tôi đang nói cho chúng tôi biết họ sẽ đến được mạng đích như thế nào. Bước tiếp theo là điền vào những feasible distance

 - Làm thế nào để tôi có được những con số trong bảng  advertised distance? Hãy nhìn vào tất cả các bộ định tuyến:
 - Router Spade rất dễ dàng. Điểm đến có khoảng cách 5 như trong hình ảnh tô pô. Điều này sẽ được quảng cáo cho router Hearts và được đặt trong bảng topology của nó.
 - Các Router Clubs sẽ học được mạng đích thông qua router Hearts và router Diamond. Router Hearts sẽ quảng cáo khoảng cách từ 5 + 4 = 9 tới các router Clubs. Vậy tại sao tôi không đặt "9" vào khoảng cách quảng cáo trong bảng? Câu hỏi hay! Hãy nhớ split-horizon? Không quảng cáo cho láng giềng của bạn bất cứ điều gì bạn học được từ họ ... router clubs không gửi thông tin về mạng này trở lại router Hearts. Để cụ thể hơn: **bất cứ điều gì bạn học trên một interface bạn không quảng cáo trở lại trên cùng một interface**.

 - Làm thế nào tôi đã nhận được đến 25? Hãy chia nhỏ nó đi: Router Spade sẽ quảng bá khoảng cách 5 tới router Hearts. Router Hearts sẽ
quảng cáo 5 + 4 = 9 về phía router Diamond. Router Diamond sẽ quảng cáo 5 + 4 + 9 = 18 đối với router clubs. Cuối cùng router clubs sẽ quảng cáo 5 + 4 + 9 + 7 = 25 đối với router Hearts. Split-horizon không được áp dụng ở đây vì các router clubs đã học được về đích đến trên một giao diện khác (router Diamond).

1. Router Spade quảng bá khoảng cách là 5 tới Hearts router.
2. Router Hearts quảng cáo khoảng cách từ 5 + 4 = 9 tới clubs router.
3. Router Clubs quảng bá khoảng cách từ 5 + 4 + 3 = 12 lên router Diamond.
4. Router Diamond quảng bá khoảng cách từ 5 + 4 + 3 + 7 = 19 tới router Hearts.

![](https://i.imgur.com/GLWmfPs.png)

 - Router Hearts đã học được khoảng cách quảng cáo từ các láng giềng và biết về các giao diện kết nối trực tiếp của chính nó để bạn có thể điền vào feasible distance. Bước cuối cùng là chọn successor..

 ![](https://i.imgur.com/Irc5zmB.png)

 - Router Spade có khoảng cách khả thi thấp nhất nên nó sẽ trở thành người successor... xuất sắc! Chúng ta hãy kiểm tra feasible successor và liệu có một đường dẫn dự phòng không:

 **- với điều kiện advertised distance của đường dự phòng phải < Feasible distance của đường chính** 

 - advertised distance của  router clubs  (25) và Diamond (19) cao hơn feasible distance của router Spade (9) nên chúng sẽ không trở thành những feasible successors. Điều này có ý nghĩa đúng không nào? Nếu những router này trở thành đường dẫn dự phòng, chúng ta sẽ có một vòng lặp! 

 - Nếu hàng xóm của bạn ở gần đích hơn tổng số đường dẫn của bạn, ít nhất bạn cũng biết rằng nó không đến đích bằng cách gửi các gói tin **thông qua router của bạn**. Có lẽ nó không phải là con đường tốt nhất nhưng chắc chắn 100% sẽ không bị lặp.

 - Đây là sự kết thúc của chương giới thiệu EIGRP! Bạn nghĩ sao? Có phải điều này mới cho bạn hoặc chỉ cần gọi lại CCNA. Hãy chắc chắn rằng bạn hiểu tất cả các khái niệm chính vì trong chương tiếp theo chúng ta sẽ đi sâu vào tài liệu

<a name=2></a>

## 2.  EIGRP Packets and Metrics (gói tin EIGRP và metric)

 - Các gói tin Hello được gửi giữa các hàng xóm của EIGRP để **phát hiện và phục hồi láng giềng** . Nếu bạn gửi gói tin hello và nhận lại chúng sau đó EIGRP sẽ tạo thành mối quan hệ láng giềng với router kia. Miễn là bạn nhận được gói tin hello từ phía bên kia EIGRP sẽ tin rằng các router khác vẫn còn đó, ngay khi bạn không nhận được chúng nữa bạn sẽ thả mối quan hệ láng giềng được gọi là **adjacency** và EIGRP có thể phải tìm một con đường khác cho các điểm đến nhất định.

 - EIGRP sử dụng RTP (reliable transport protcol) và chức năng của nó là cung cấp gói tin EIGRP giữa các nước láng giềng một cách đáng tin cậy và có trật tự. Nó có thể sử dụng multicast hoặc unicast và để giữ mọi thứ được hiệu quả không phải tất cả các gói tin đều được gửi một cách tin cậy. Đáng tin cậy có nghĩa là khi chúng ta gửi một gói tin chúng tôi muốn nhận được một **sự thừa nhận ( acknowledgment)** từ phía bên kia để đảm bảo rằng họ đã nhận được nó.

 ![](https://i.imgur.com/1rColq2.png)

 - Trong ví dụ này chúng ta có 4 router đều chạy EIGRP. gói tin hello được gửi giữa các router để hình thành adjacencies. Như bạn thấy router Lizzy đang gửi 3 gói tin hello dành cho router Jack, John và Lizzy.
 - Có 2 câu hỏi mà chúng ta có thể tự hỏi mình ở đây:
 <ul>
 <li>Là nó thực sự hữu ích khigửi 3 gói tin hello khác nhau trên một link. </li>
 <li>Có cần một gói hello nhận được một ACK trở lại?</li>
 </ul>

 - Gửi 3 gói tin trên cùng một liên kết không thực sự hữu ích vì vậy thay vì làm thế EIGRP này sẽ gửi gói tin hello bằng cách sử dụng multicast trên multi-access như Ethernet.
 - Các gói tin Hello không cần có ACK vì EIGRP sử dụng **holddown time** . Nếu một bộ định tuyến không nhận được gói tin hello trong một khoảng thời gian X nó sẽ bỏ quan hệ láng giềng adjacencies. Vì vậy, các gói tin cần được ACK? Hãy suy nghĩ về thông tin định tuyến, nếu có thay đổi trong mạng mà bạn muốn đảm bảo rằng tất cả các bộ định tuyến nhận được bản cập nhật định tuyến này

 - Để tôi chỉ cho bạn tất cả các gói tin EIGRP khác:
 <ul>
 <li>Hello</li>
 <li>Update</li>
 <li>Query</li>
 <li>Reply</li>
 <li>ACK (Acknowledgement)</li>
 </ul>
 - Các gói tin **Hello**: được sử dụng để phát hiện hàng xóm. Ngay khi bạn gửi gói tin hello và nhận được chúng, các bộ định tuyến EIGRP của bạn sẽ cố gắng hình thành hàng xóm lân cận(adjacencies).

 - Các gói tin **Update**: có thông tin định tuyến và được gửi đi đáng tin cậy cho bất cứ router nào yêu cầu thông tin này. Các gói tin cập nhật có thể được gửi tới một hàng xóm đơn sử dụng unicast hoặc cho một nhóm hàng xóm sử dụng multicast

 - Các gói tin **query** :được sử dụng khi bộ định tuyến EIGRP của bạn bị mất thông tin về một mạng nhất định và không có bất kỳ đường dẫn sao lưu nào . Điều xảy ra là router của bạn sẽ gửi các gói tin truy vấn đến các láng giềng của họ yêu cầu họ nếu họ gửi lại nếu có thông tin về mạng cụ thể này.

 - các gói tin **reply**: được sử dụng để đáp lại các gói truy vấn và được gửi theo hướng đáng tin cậy.

 - Các gói ACK được sử dụng để xác nhận việc nhận các gói Update, query và reply. Các gói tin ACK được gửi bằng cách sử dụng unicast.

 ![](https://i.imgur.com/PjJg2w0.png)

 -Thay vì chỉ sử dụng một bảng định tuyến duy nhất EIGRP sẽ sử dụng nhiều bảng. Đầu tiên là **neighbor table **và đây là nơi EIGRP lưu trữ tất cả thông tin của các hàng xóm kết nối trực tiếp. Sau khi chúng đã trở thành láng giềng các router sẽ trao đổi thông tin định tuyến được lưu trong topology của EIGRP. Có thể có nhiều mục cho một mạng trong bảng tô pô( nhiều đường để đi đến 1 mạng). Thông tin tốt nhất về đường đi sẽ được sao chép từ bảng tô pô EIGRP vào bảng định tuyến.

 - Bây giờ bạn đã biết về tất cả các gói khác nhau và các bảng EIGRP hãy nhìn vào quá trình tổng thể trở thành những người hàng xóm EIGRP và trao đổi thông tin định tuyến:

![](https://i.imgur.com/8xo8kj3.png)

 - 1 chúng ta có 2 router tên gọi là jack và john , chúng đều được cấu hình EIGRP . ngay khi chúng ta cho phép các interface sẽ bắt đầu gửi các gói hello. trong ví dụ trên , router jack là router đầu tiên gửi gói hello

 ![](https://i.imgur.com/14I5vpS.png)

 - 2 ngay khi router john nhận được gói hello từ jack, nó sẽ trả lời lại bằng cách gửi gói Update chứa tất cả thông tin định tuyến mà nó có trong routing table. Các tuyến đường duy nhất không được gửi trên interface này là tuyến mà John đã học được trên interface này do split-horizon. Gói cập nhật mà router John sẽ gửi có bit khởi tạo được bật lên để chúng ta biết đây là "quá trình khởi tạo". Tại thời điểm này vẫn không có quan hệ adjacency  cho đến khi router John gửi xong  một gói tin hello cho Jack.

 ![](https://i.imgur.com/mZ39bKi.png)

 - 3 Router Jack tất nhiên không phải là người duy nhất gửi gói tin hello. Ngay khi router John gửi một gói tin chào tới Jack chúng ta có thể tiếp tục thiết lập mối quan hệ láng giềng

 ![](https://i.imgur.com/MqbTclo.png)

 - 4 sau khi cả hai trao đổi qua lại gói tin hello chúng sẽ thiết lập được quan hệ adjacency . Router Jack sẽ gửi một ACK để cho John biết rằng anh ta đã nhận được các gói tin cập nhật. nhưng thông tin định tuyến trong gói tin cập nhật sẽ được lưu lại trong bảng topology của EIGRP .

 ![](https://i.imgur.com/iPt2GMZ.png)

 - 5 Router John cũng chờ đợi nhận được thông tin định tuyến vì vậy Jack sẽ gửi các gói cập nhật cho John, john sẽ lưu thông tin này trong bảng topology EIGRP của nó. 
 ![](https://i.imgur.com/ycr2dBY.png)

 - 6 sau khi nhận được gói tin cập nhật từ jack , john sẽ gửi ACK cho jack để nói cho jack biết rằng mọi thứ vẫn bình thường .

 - ngay sau khi cả hai router trao đổi thông tin định tuyến cho nhau chúng sẽ chọn con đường tốt nhất để đi đến mỗi đích đến cụ thể và copy chúng vào routing table , chúng được gọi là **successor**

 - Bạn muốn xem những gì xảy ra giống như trên một router thực sự? Hãy sử dụng topo sau và xem những gì xảy ra:
 ![](https://i.imgur.com/QgNObg6.png)

 - Đây là sơ đồ mà tôi sẽ sử dụng để định cấu hình EIGRP. Mục tiêu của tôi là có kết nối đầy đủ và đây là các cấu hình:

![](https://i.imgur.com/I9FamM1.png)

 - hãy phân thích nó ra. câu lệnh **Router EIGRP  1 ** sẽ khởi động thiết lập EIGRP bằng cách sử dụng AS( autonomous system) số 1. con số này phải giống ở cả 2 router nếu không chúng sẽ không thể trở thành EIGRP neighbor.

 - **No auto-summary** là cần thiết bởi vì mặc định EIGRP sẽ hoạt động giống như một giao thức định tuyến classful có nghĩa là nó sẽ không quảng cáo subnet mask cùng thông tin định tuyến. trong trường hợp này , nó có nghĩa là 1.1.1.0/24 và 2.2.2.0/24 sẽ được quảng bá với 1.0.0.0/8 và 2.0.0.0/8. tắt tính năng tự động gộp mạng ( auto-summary) sẽ đảm bảo router gửi kèm subnet mask

 - **network 1.1.1.0 0.0.0.255** có nghĩa là tôi quảng cáo các mạng tồn tại trên các interface thuộc phạm vi 1.1.1.0 - 1.1.1.255. nếu tôi không chỉ rõ wildcard bạn sẽ tìm thấy mạng 1.0.0.0 trong cấu hình của mình. có vấn đề gì không? không hay có. Điều tương tự cũng áp dụng cho "mạng 2.2.2.0 / 24". Nó sẽ làm việc nhưng cũng có nghĩa là mọi giao diện nằm trong khoảng 1.0.0.0/8 hoặc 2.0.0.0/8 sẽ chạy EIGRP. mạng 192.168.1.0 không có wildcard vì tôi sữ dụng nó ở lớp c , và octet đầu là 192 củng thuộc lớp c . nếu bạn đang làm lab và bạn rất lười biếng thì bạn có thể gõ **network 0.0.0.0 ** nó sẽ kích hoạt tất cả các mạng trên tất cả các interface của bạn để tham gia vào quảng bá cho router khác ..... tất nhiên nếu đó là điều bạn muốn , còn không thì đừng làm vậy. 

 - Hãy thực hiện debug trên router John để xem điều gì đang xảy ra: 
 ![](https://i.imgur.com/ZCG6bNx.png)

 - như bạn thấy , chúng ta có rất nhiều tùy chọn debug cho EIGRP , tôi muốn thấy gói hello, nên tôi gõ :
 ![](https://i.imgur.com/BwsE8j3.png)

 - trông tốt lắm dường như chúng tôi đã nhận được một gói hello từ router Jack.
 ![](https://i.imgur.com/n1HKCyf.png)

 - và ta củng đang gửi gói hello cho router jack như vậy.
 ![](https://i.imgur.com/ELxZEZ4.png)

 ![](https://i.imgur.com/MaDJQxz.png)

 - bạn có thể thấy chúng ta đã có quan hệ neighbor adjacency.

 ![](https://i.imgur.com/p2iVDJT.png)

 - điều thú vị là jack củng gửi gói hello cho loopback 0 của nó để nó nhận được và phản hồi lại. điều này là bình thường vì câu lệnh **network** làm 2 việc :
 <ul>
 <li>gửi các gói tin EIGRP đến các interface thuộc phạm vi của lệnh network </li>
 <li>quảng bá các mạng thuộc interface được cấu hình EIGRP </li>
 </ul>
 
 - Vậy bạn phải làm gì khi muốn quảng cáo một mạng mà không gửi các gói EIGRP trên 1 cổng và vẫn tạo ra các hàng xóm của EIGRP? Sử dụng lệnh **passive interface.**

 ![](https://i.imgur.com/zUuQE0h.png)

 - điều này sẽ làm việc quảng bá mạng 2.2.2.2/24 cho jack mà không gửi gói EIGRP cho loopback 0 nữa

 ![](https://i.imgur.com/qGV2gEZ.png)

 - Nếu bạn phải cấu hình một bộ định tuyến ISP với  hơn 50 interface có lẽ bạn không muốn gõ lệnh này trên mỗi giao diện đó. Bạn cũng có thể cấu hình   passive-interface default và chỉ kích hoạt các giao diện mà bạn muốn chạy EIGRP trên đó

 - Chúng ta hãy xem xét một quá trình debug của một số gói tin cập nhật EIGRP. Tôi sẽ xóa EIGRP  neighbor adjacency  để xem nó trông như thế nào:
 ![](https://i.imgur.com/DWRMCEJ.png)

 - hãy reset lại neighbor adjacency trên router jack. 
 ![](https://i.imgur.com/WUNDhoU.png)

 - bạn có thể thấy router jack làm rất tốt , nó bảo router john là hãy xóa quan hệ neighbor adjacency. 

 ![](https://i.imgur.com/yynOAQs.png)

 - Router Jack trở lại vai trò của minh và neighbor adjacency EIGRP của chúng  đã được thiết lập lại.
 ![](https://i.imgur.com/PSwF4op.png)

 - Ở đây bạn có thể thấy router John đang đặt một gói cập nhật trong hàng đợi của nó cho router Jack. John cũng đang nhận một gói cập nhật từ router Jack và sau đó gửi gói tin cập nhật riêng của nó. Bạn sẽ thấy một vài gói cập nhật đang bay qua lại.
 ![](https://i.imgur.com/52tJucc.png)

 - chúng ta củng có thể kiểm tra gói ACK bằng câu lệnh debug ack Packets. 

 ![](https://i.imgur.com/ktDoTH5.png)

 - Chúng ta sẽ thiết lập lại neighbor adjacency EIGRP do đó các gói tin cập nhật bị gửi lại.
 ![](https://i.imgur.com/tgskJ9s.png)

 - Đây là những gói ack để phản hồi một số gói cập nhật. Nếu bạn muốn xem toàn bộ quá trình chúng tôi có thể kết hợp một số gỡ lỗi.
![](https://i.imgur.com/FrCnxmX.png)

 - Đây là cách bạn kích hoạt gỡ lỗi cho tất cả các gói EIGRP.
 ![](https://i.imgur.com/qbCJIgh.png)

 - cách để bạn loại bỏ mọi debug .

 - khởi động lại quá trình thiét lâị neighbor adjacency ta sẽ có. 

 ![](https://i.imgur.com/iACGtAn.png) 
 ![](https://i.imgur.com/SWcSJJJ.png)

 - Điều này sẽ cho bạn thấy toàn bộ quá trình gửi gói tin hello với nhau, trở thành những người hàng xóm của EIGRP, trao đổi các bản cập nhật và gửi ack.

 ![](https://i.imgur.com/fUzrGB5.png)

 - Đây là lệnh cuối cùng tôi muốn cho bạn thấy ngay bây giờ **show ip protocols** là một lệnh rất hữu ích và mạnh mẽ trong kho công cụ của CCNP .Nó sẽ cho bạn thấy những network đang định tuyến, các passive interface và administrative distance . Xem khoảng cách hành chính bên ngoài là 170? Chúng ta sẽ nói về điều đó trong chương Redistribution. lệnh này không chỉ dành cho EIGRP nó sẽ cho bạn thấy tất cả các giao thức định tuyến khác. 

 - bây giờ hãy Dừng gỡ lỗi và hãy tiếp tục bằng cách nhìn vào các bảng EIGRP khác nhau cụ thể là :
 <ul>
 <li>EIGRP Neighbor table</li>
 <li>EIGRP Topology table</li>
 <li>Routing table</li>
 </ul>

 ![](https://i.imgur.com/afdCcys.png)

 - trở lại với Router Jack và John và tôi sẽ cho bạn thấy neighbor table EIGRP trông giống như thế nào trên một mạng thực sự:

 ![](https://i.imgur.com/mzwcP7r.png)

 - Trong đầu ra ở trên, tôi đang nhìn vào bảng neighbor của EIGRP của router Jack. Như bạn thấy chúng ta có một hàng xóm (192.168.12.2) mà sẽ là router John trên interface FastEthernet 0/0. Chúng ta tìm thấy gì ở đây?.
 <ul>
 <li>**H (handle)**: Ở đây bạn sẽ tìm thấy thứ tự khi neighbor adjacency được thiết lập. Hàng xóm đầu tiên của bạn sẽ có giá trị là 0, hàng xóm thứ hai có giá trị là 1 và như vậy.</li> 
 <li>**Hold Uptime (giây)**: đây là bộ đếm thời gian holddown của mỗi EIGRP neighbor. Một khi bộ đếm thời gian này hết hạn, chúng ta sẽ thả hàng xóm láng giềng. Bộ hẹn giờ giữ mặc định là 15 giây. Trên các phiên bản IOS cũ hơn chỉ có một gói tin hello sẽ thiết lập lại bộ đếm thời gian holddown nhưng trên các phiên bản IOS mới hơn bất kỳ gói EIGRP sau lần chào đầu tiên sẽ đặt lại bộ đếm thời gian holddown.</li>
 <li>**SRTT (Smooth round-trip time)**: Số mili giây cần để gửi gói tin EIGRP tới hàng xóm của bạn và nhận lại gói tin xác nhận.</li>
 <li>**RTO (Retransmission timeout)**: Khoảng thời gian tính bằng mili giây mà EIGRP đợi trước khi truyền lại gói tin từ hàng đợi retransmission tới hàng xóm này</li>
 <li>**Q Cnt (Q count):** Số lượng các gói tin EIGRP (Cập nhật, Truy vấn hoặc Trả lời) trong hàng đợi đang chờ truyền. Lý tưởng là bạn muốn con số này là 0 nếu không nó có thể là một dấu hiệu tắc nghẽn trên mạng.</li>
 <li>**Seq Num (Sequence number):** Sẽ hiển thị số thứ tự của gói cập nhật, truy vấn hoặc trả lời cuối cùng mà bạn nhận được từ hàng xóm của EIGRP.</li>
 </ul>

 - Tuyệt vời vì vậy đó là cách EIGRP lưu trữ thông tin hàng xóm! Điểm dừng tiếp theo của chúng tôi tất nhiên là để xem bảng EIGRP Topology:
 ![](https://i.imgur.com/wjKTABN.png)

 - Bây giờ đó là rất nhiều thông tin để xem! Hãy để tôi phá vỡ cho bạn từng khối:

 ![](https://i.imgur.com/upCqMLv.png)

 - Nếu bạn nhìn vào phông chữ màu đỏ bạn có thể thấy rằng chúng ta đang nhìn vào bảng cấu trúc EIGRP cho **AS (Autonomous System)** số 1. Lưu ý rằng số AS phải khớp với các router EIGRP để trở thành hàng xóm!

 ![](https://i.imgur.com/o6kPjUd.png)

 - Nhìn vào những mã ... Cập nhật, Truy vấn và Trả lời đã nói đến trong một vài trang trước. Hãy tập trung vào những mã mà tôi đã không giải thích trước đây:
 <ul>
 <li>**passive:** Thụ động là tốt ... chúng tôi thích định tuyến thông tin phải thụ động có nghĩa là chúng ta đã học được thông tin về một mạng và không có thay đổi trong bảng tô pô.</li>
 <li>**active:** active không tốt vì nó có nghĩa là chúng ta đã mất thông tin về một mạng nhất định và EIGRP không biết cách nào khác để truy cập vào mạng này. Nó sẽ đi vào chế độ active và gửi các gói truy vấn đến TẤT CẢ các hàng xóm của nó hỏi họ nếu họ biết làm thế nào để tiếp cận mạng này.</li>
 <li>**Reply Status:** EIGRP sẽ theo dõi tất cả các gói truy vấn mà nó đã gửi đến hàng xóm vì bạn cần trả lời. Bằng cách thiết lập cờ trạng thái phản hồi, nó sẽ làm điều này.</li>
 <li>**Sia Status (Stuck in Active):** Đây là một lỗi ... nó có nghĩa là EIGRP đã không nhận được trả lời cho một gói truy vấn từ một trong những hàng xóm trong thời gian cho phép (khoảng 3 phút). Khi điều này xảy ra EIGRP sẽ bỏ neighbor adjacency và nó do bị va chạm trong hoạt động. ta sẽ tìm hiểu Thêm về điều này sau!</li>
 </ul>

 ![](https://i.imgur.com/l2xgFGL.png)

 - Một điều nữa để cho bạn thấy! Chúng ta hãy nhìn vào một mục nhập của một tiền tố ... trong trường hợp này là 2.2.2.0/24 và chia nhỏ thành nhiều phần:
 <ul>
 <li>**P 2.2.2.0/24:** **P** là viết tắt của **passive **và đó là cách chúng ta thích nó! Như bạn thấy, EIGRP lưu trữ mạng và subnet mask.</li>
 <li>**1 successor:**  Con đường tốt nhất để đến một mạng nhất định được gọi là **người kế nhiệm (successor)**. Có thể có đường dẫn dự phòng mà EIGRP gọi là **người kế thừa khả thi (feasible successor)**. Trong trường hợp này chỉ có một cách để đến đích. và không có feasible successor</li>
 <li>**FD is 156160**: FD viết tắt của **Feasible distance ** và trong tiếng anh chúng ta gọi đó là tổng khoảng cách để đến được đích </li>
 <li>**Via 192.168.12.2:** đó là địa chỉ IP của hàng xóm , nơi mà chúng ta sẽ gửi gói tin đi qua đó để đến được mạng 2.2.2.2/24</li>
 <li>**(156160/128256):** Giá trị đầu tiên là **feasible distance**. Giá trị thứ hai là khoảng **advertised distance**. ở EIGRP hàng xóm của bạn sẽ báo cáo cho bạn cách xa anh ta bao nhiêu để đến được mạng 2.2.2.0/24 và điều này được lưu như là **advertised distance**.</li>
 <li>**FastEthernet 0/0**: đây là một điều dễ dàng, nó là cổng của bạn và được dùng để gửi gói tin đi ra ngoài để đến được mạng cần đến </li>
 </ul>

 - Điều này có ý nghĩa gì với bạn hay không? Hiểu bảng topology EIGRP rất quan trọng để khắc phục sự cố hoặc khi chúng tôi bắt đầu làm việc với cân bằng tải (load balancing).

 ![](https://i.imgur.com/GTiW22G.png)

 - Thông tin tốt nhất từ bảng cấu trúc EIGRP sẽ được sao chép vào bảng định tuyến. Chúng ta tìm thấy gì ở đây?
 <ul>
 <li>**D (DUAL or Diffusing Update Algorithm**: DUAL là thuật toán đằng sau EIGRP đó là lý do tại sao chúng ta tìm thấy D ở đây. Tại sao chúng ta không sử dụng E cho EIGRP? Điều đó sẽ tốt đẹp hơn nhưng ký hiệu E đã được sử dụng cho EGP (External Gateway Protocol) là một giao thức định tuyến cũ mà chúng ta không sử dụng nữa.</li>
 <li>**2.2.2.0 [90/156160]**: Bạn có nhận ra những giá trị này? Thứ nhất là khoảng cách hành chính(administrative distance) là 90 đối với EIGRP, OSPF là 110 và RIP là 120 . 156160 là feasible distance cho mạng này.</li>
 <li>**Via 192.168.12.2 01:31:17, FastEthernet 0/0:** 192.168.12.2 là địa chỉ hop tiếp theo để truy cập vào mạng này. 01:31:17 là thời gian bao lâu mạng này đã được trong bảng định tuyến. Trong trường hợp này là 1 giờ, 31 phút và 17 giây. Bạn cũng có thể thấy làm thế nào để tiếp cận địa chỉ hop tiếp theo đó là qua cổng FastEthernet 0/0.</li>
 </ul>

 - Một điều nữa chúng ta phải nói về ... các metric của  EIGRP! Trong phần giới thiệu của tôi, tôi đã cho thấy các giá trị thực sự thấp vì dễ giải thích EIGRP theo cách đó. Trong các ví dụ ở trên, bạn có thể thấy rằng các giá trị feasible distance và advertised cao hơn một chút khiến chúng gây phiền nhiễu khi hoạt động. Chúng ta hãy nhìn vào các chỉ số EIGRP và công thức.

 - Hãy bắt đầu với công thức mà EIGRP sử dụng:

 - ***EIGRP Metric = 256*((K1*Bw) + (K2*Bw)/(256-Load) + K3*Delay)*(K5/(Reliability + K4)))**

 - Ewww ... có vẻ tệ nhỉ! Đừng lo lắng ... bạn không phải nhớ công thức này! Nếu bạn nhìn vào nó, bạn có thể thấy rằng nó kết hợp băng thông, tải, chậm trễ và độ tin cậy và bạn có thể thấy các giá trị K1, K2, K3, K4 và K5. Nếu bạn học CCNA bạn có thể đã nhìn thấy và / hoặc học được danh sách sau đây:
 <ul>
 <li>Bandwidth (K1)</li>
 <li>Load (K2)</li>
 <li>Delay (K3)</li>
 <li>Reliability (K4)</li>
 <li>MTU (K5)</li>
 </ul>
 - Kỹ thuật này là không chính xác. K1 không tương ứng 1: 1 với băng thông, K2 không tương ứng 1: 1 với tải, không chậm trễ với K3 vv. Các giá trị K này chỉ là các con số để quy mô số trong phép tính số liệu. Chúng ta có thể thấy những giá trị K được bật hoặc tắt theo mặc định

 ![](https://i.imgur.com/PdRzHrq.png)

 - Trong ví dụ này, nơi tôi sử dụng lệnh ** show ip protocols**, bạn có thể thấy K-values được bật theo mặc định. Chỉ có K1 và K3 được bật theo mặc định. Hãy đi qua các thành phần số liệu khác nhau để xem chúng là gì:

 - *Bandwidth:* 

 ![](https://i.imgur.com/4NwSvzv.png)

 - nếu bạn dùng lệnh *show ip interface FastEthernet 0/0** bạn có thể thấy thông tin về cổng đó . trong ví dụ trên chỉ cho ta thấy 1 phần của kết quả trả về . bạn có thể thấy Bandwidth là 100000 Kb , đó là 1 cổng 100Mb 

 ![](https://i.imgur.com/IhkyF6Z.png)

 - Băng thông là một giá trị tĩnh có thể thay đổi bằng cách sử dụng lệnh ** bandwidth **. Hãy ghi nhớ rằng điều này không thay đổi băng thông thực tế của cổng! Lệnh này chỉ được sử dụng để ảnh hưởng đến các giao thức định tuyến như EIGRP. Nó không giống như việc bạn có thể làm chậm tín hiệu điện thông qua một dây ... nếu bạn muốn giới hạn giao thông trên một giao diện bạn sẽ cần QoS (Chất lượng dịch vụ) đó là một câu chuyện cho một ngày khác. 

 ![](https://i.imgur.com/vm6OTXm.png)

 - Ở đây bạn thấy kết quả của việc thay đổi băng thông trên giao diện. Một điều cần nhớ là EIGRP sẽ sử dụng băng thông thấp nhất trong đường dẫn từ A đến B (vì đây là nút cổ chai).

 - **load:** 

 ![](https://i.imgur.com/8wMsS48.png)

 - Load sẽ cho bạn thấy mức độ hoạt động của giao diện dựa trên tốc độ gói tin và băng thông trên giao diện. Đây là một giá trị có thể thay đổi theo thời gian vì vậy nó là một giá trị động. 

 - **delay:**

 ![](https://i.imgur.com/l8MwGTD.png)

 - Delay phản ánh thời gian cần thiết để các gói tin đi qua đường dẫn và là một giá trị tĩnh. Cisco IOS sẽ có các giá trị trễ mặc định cho các loại cổng khác nhau. Một cổng FastEthernet có một delay mặc định là 100 usec(micro seconds).
 ![](https://i.imgur.com/C1rvKNt.png)

 - Nếu bạn sử dụng câu lệnh delay bạn có thể thay đổi giá trị giá trị này ảnh hưởng đến routing protocols giống EIGRP. nhưng nó không thực sự thay đổi delay của giao diện này, nó được dùng chỉ để ảnh hưởng đến giao thức định tuyến
 ![](https://i.imgur.com/qRJv3cQ.png)

 - Ở trên bạn thấy delay mà tôi đã thay đổi. EIGRP sẽ **tích lũy tất cả các giá trị delay trong đường dẫn từ A đến B ( tức là tổng delay)**.

 - **Reliability:**

 - ![](https://i.imgur.com/pVm3w7h.png)

 - Reliability ở đây 255/255 là 100%. Điều này có nghĩa là bạn không có vấn đề về lớp physical hoặc lớp data-link. Nếu bạn đang gặp vấn đề giá trị này sẽ giảm. đây là một giá trị có thể thay đổi , một giá trị động

 - **MTU** 

 ![](https://i.imgur.com/fKmnZys.png)

 - MTU hoặc Maximum Transmission Unit là đơn vị dữ liệu đang được trao đổi giữa các hàng xóm của EIGRP nhưng không được sử dụng để tính toán metric. MTU là giá trị tối đa của 1 gói dữ liệu được đóng gói, nếu gói tin có dung lượng lớn hơn MTU gói tin sẽ được cắt nhỏ ra , giả sử có 1 gói dung lương 4700 byte thì sau khi đến router nó sẽ chia nhỏ ra thành 3 gói 1500 byte ( 1500 là giá trị mặc định của MTU) và 1 gói nặng 200byte sau đó chuyển tiếp đi.

 - Theo mặc định chỉ K1 và K3 được kích hoạt và chúng tôi không sử dụng K2 hoặc K4. Điều này có nghĩa là chỉ có băng thông và độ trễ được sử dụng trong công thức.

 - Tại sao không? Bởi vì tải và độ tin cậy là giá trị động và chúng có thể thay đổi theo thời gian. Bạn không muốn các router EIGRP của mình tính toán 24/7 và gửi các cập nhật cho nhau chỉ vì tải hoặc độ tin cậy của giao diện đã thay đổi. Chúng tôi muốn các giao thức định tuyến được tốt đẹp và yên tĩnh và chỉ dựa vào các quyết định định tuyến của họ về các giá trị tĩnh như băng thông và sự chậm trễ. Nếu bạn chỉ sử dụng hai giá trị tĩnh này thì các router EIGRP của chúng ta không phải tính toán lại trừ khi một interface bị down hoặc một router đã chết.

 - từ việc chỉ có K1 và K3 được kích hoạt, chúng ta có thể đơn giản hóa công thức EIGRP:

**Metric = bandwidth (slowest link) + delay (sum of delays)**
 <ul>
 <li>Bandwidth: [10^7 / bandwidth nhỏ nhất trên tuyến đường đơn vị tính là Kbps] * 256.</li>
 <li>Delay: tổng của các delay trên tuyến đường nhân với 256 (đơn vị của delay là 10 microseconds)</li>
 </ul>

 - nên công thức sẽ trở thành :

**Metric = (10^7 / minimum bandwidth) * 256 + (sum of delays) * 256**

 - Số nhân 256 được thực hiện vì vậy EIGRP tương thích với IGRP (người tiền nhiệm của EIGRP). Hãy để tôi chỉ cho bạn một ví dụ để chúng ta có thể chia nhỏ công thức này.
![](https://i.imgur.com/gGvzUWQ.png)

 - Chúng tôi đang nhìn vào R1 và tính toán khoảng cách để đến R5. Như bạn thấy, có một đường dẫn ở trên với một số giao diện T1 và một link 64kbps. Đường dẫn dưới có hai link 256kbps.

 - Một giao diện T1 có băng thông 1,554Mbit rõ ràng hơn 256kbps nhưng nút cổ chai trên đường dẫn là đường truyền 64kbps. Hãy ném những con số này cho đường dẫn trên trong công thức số liệu EIGRP và xem điều gì sẽ xảy ra:

 - Băng thông thấp nhất trong đường dẫn phía trên là đường truyền 64 kbps để tính toán băng thông EIGRP sẽ làm như sau:
Băng thông = (107 / link chậm nhất) * 256
Băng thông = (10.000.000 / 64) * 256 = 156.250 * 256 = 40.000.000

 - bây giờ chúng ta sẽ nhìn vào công thức tính delay cho đường dẫn trên. 

- delay = [tổng delay]*256.
- delay = [1000+1000+1000] * 256.
- Delay = 768,000.

 - Hãy cộng các số đó lại với nhau và chúng tôi sẽ có tổng số liệu:

 - Metric = bandwidth + delay
 Metric = 40,000,000 + 768,000
 Metric = 40,768,000

 - bây giờ chúng ta hãy làm tương tự với đường phía dưới.

 - Độ rộng băng thông thấp nhất trong đường link bên dưới là kết nối 256 kbps nên tính toán băng thông EIGRP sẽ như sau:

 - Bandwidth = (10^7 / link chậm nhất) * 256
 - Bandwidth = (10,000,000 / 256) * 256 = 39062.5 * 256 = 10,000,000

 - Bây giờ chúng ta hãy nhìn vào phép tính trễ cho đường dẫn dưới:

 - Delay = [tổng delay] * 256
 - Delay = [1000+1000] * 256
 - Delay = 512,000

 - Hãy cộng các số đó lại với nhau và chúng tôi sẽ có tổng metric.

 - Metric = bandwidth + delay
 - Metric = 10,000,000 + 512,000
 - Metric = 10,512,000.

 - metric đường trên = 40,768,000
 - metric đường dưới = 10,512,000

 - đường có metric thấp nhất sẽ được dùng làm successor và được lưu lại trong bảng định tuyến , trong ví dụ này là đường phía dưới sẽ được dùng làm successor.

 - Có lẽ bạn đang tự hỏi công thức trông như thế nào nếu bạn cho phép tải (K2) và độ tin cậy (K4), nó sẽ là :

  - Metric = [K1*bandwidth + ((K2*bandwidth)/(256-load))+K3*delay]

  - Nếu MTU (K5) không bằng 0: 
  - Metric = Metric*[K5/(reliability+K4)]

  - Phù! Điều này có làm cho đầu của bạn quay cuồng? Tôi nghĩ rằng bạn và tôi đều đồng ý rằng chúng ta nên cho phép EIGRP tính toán số liệu chứ không phải thêm điều gì cả  (đó là lý do tại sao chúng tôi có bộ định tuyến đúng!). Bài học quan trọng tôi muốn giới thiệu với các bạn ở đây là EIGRP sử dụng băng thông chậm nhất trên đường đi và tổng thời gian chậm trễ. Bạn không cần phải biết rõ công thức này bằng cách hiểu nó. Không cần phải thực hiện bất kỳ tính toán thủ công nào trong kỳ thi!

  - Các số liệu trong EIGRP là một cực hình để làm việc vì các giá trị rất lớn! Nếu bạn muốn thực hành với EIGRP, bạn có thể thử vô hiệu hóa tất cả các giá trị K trừ K3. Điều này sẽ làm cho EIGRP chỉ sử dụng sự chậm trễ làm thước đo. Các giá trị số liệu sẽ thấp hơn và dễ dàng hơn để làm việc vì bạn không phải nghĩ đến băng thông thấp nhất trong đường dẫn. Tôi muốn làm điều này khi tôi dạy cho mọi người cách tính toán những người kế thừa khả thi và định cấu hình cân bằng tải EIGRP

  - Cảm thấy thích chơi với một số các chỉ số và cân bằng tải ? Hãy thử với các phòng bài lab sau:
 http://gns3vault.com/EIGRP/eigrp-maximum-path-and-variance.html
 http://gns3vault.com/EIGRP/eigrp-intermediate.html

<a name="3"></a>
## 3. 3. EIGRP Summarization

 - Nếu bạn đã học và vượt qua CCNA bạn có thể có một ý tưởng tại sao chúng ta sử dụng tóm tắt. 
 <ul>
 <li>Giảm kích thước của bảng định tuyến.</li>
 <li>Cập nhật định tuyến ít hơn.</li>
 </ul>

 - EIGRP có hai cách tóm tắt các mạng:
 - Tóm tắt tự động:
 <ul>
 <li>Các mạng con được tóm tắt cho mạng classful</li>
 <li>đây là mặc định của EIGRP </li>
 </ul>

 - tóm tắt bằng tay
 
 - Bạn nên tắt tính năng tự động tóm tắt của EIGRP vì nó có thể gây ra các vấn đề về định tuyến. 
 ![](https://i.imgur.com/ZzVHP6Y.png)

 - Xemmô hình ở trên. Chúng ta có 3 router và chúng ta đang cấu hình EIGRP. Lưu ý các mạng 172.16.1.0 và 172.16.2.0. EIGRP sẽ tổng hợp vào mạng classful theo mặc định.

 ![](https://i.imgur.com/KVnm8Nv.png)

 - Router Spade và router clubs không gửi subnet mask cùng với bản cập nhật định tuyến để nó quảng cáo mạng classful là 172.16.0.0 trong trường hợp này. Vậy điều gì xảy ra với router Hearts? Nó cho rằng nó có thể đạt đến mạng 172.16.0.0 bằng cách gửi các gói tin sang trái hoặc phải và nếu số liệu bằng nhau thì nó sẽ cố gắng cân bằng tải. Rõ ràng điều này sẽ gây ra vấn đề.

 ![](https://i.imgur.com/r6S5264.png)

 - Gõ vào lệnh no auto-summary để đảm bảo rằng EIGRP sử dụng classless và gửi subnet mask kèm theo.
![](https://i.imgur.com/bY12I61.png)

 - Đây là điều chúng tôi muốn đạt được. Router Spade và Clubs sẽ gửi subnet mask với các gói tin cập nhật EIGRP của họ.

 - Chúng ta hãy xem xét tổng hợp bằng tay là rất vui vẻ hơn. Trong hình dưới đây chúng ta có router Jack và John, router Jack có các mạng sau đây cấu hình:

 192.168.0.0 / 24
 192.168.1.0 / 24
 192.168.2.0 / 24
 192.168.3.0 / 24

 - Khi chúng ta cấu hình EIGRP, tất cả 4 mạng sẽ được quảng cáo và được nhìn thấy trong bảng định tuyến của Router John
 ![](https://i.imgur.com/39iznSK.png)

 - đây là router table của john.

 ![](https://i.imgur.com/F8IUUKz.png)

 - Hãy cấu hình một bảng tóm tắt cho router Jack để giảm kích thước của bảng định tuyến của router John. Tạo các tóm tắt cho EIGRP rất dễ dàng vì bạn có thể thực hiện nó trên bất kỳ interface nào bạn thích.

 ![](https://i.imgur.com/QjxUlS8.png)

 - Tôi tóm tắt 4 mạng này thành 192.168.0.0 / 22. Bạn cần chỉ định số AS và subnet mask để gửi kèm theo mạng. Như bạn thấy, nó được đồng bộ lại với router John.

 ![](https://i.imgur.com/lgDN3pk.png)

 - Đây là những gì router John trông thấy bây giờ. Chúng tôi giảm bảng định tuyến của nó từ 4 mục sang chỉ 1 mục nhập.
![](https://i.imgur.com/uZVkZrS.png)

 - Router John không phải là người duy nhất có bảng định tuyến thay đổi. Nhìn vào router Jack phía trên và kiểm tra mục nhập cuối cùng. 192.168.0.0/22 đã được tạo ra các gói tin gửi đến Null0. Giao diện Null0 của chúng tôi giống như một lỗ đen hút các gói không bao giờ trở lại ... ouch! Tại sao EIGRP lại làm điều này và nó là gì? Hãy để tôi chỉ cho bạn một ví dụ khác.

 ![](https://i.imgur.com/45ormCb.png)

 - Ví dụ trước đây là một ví dụ A + của tổng hợp vì tôi tóm tắt các mạng sau đây:
 192.168.0.0 /24
 192.168.1.0 /24
 192.168.2.0 /24
 192.168.3.0 /24

 - Vào 192.168.0.0 / 22 đó là một kết hợp hoàn hảo.

 - Nếu bạn nhìn vào ví dụ trên, tôi đã thay đổi. Tôi tạo ra bản tóm tắt 192.168.0.0/16 mà router Jack đang quảng cáo hướng tới router John. Đây là một ví dụ-C! Tóm tắt đang hoạt động nhưng tôi đang quảng cáo một phạm vi rộng lớn các mạng mà tôi không có.

 - Hãy nhìn vào bảng định tuyến của router John:
![](https://i.imgur.com/5nHlMjX.png)

 - Có 2 điều cần đề cập ở đây:
 <ul>
 <li>Bây giờ chúng ta có mục nhập 192.168.0.0/16 trong bảng định tuyến của chúng ta.</li>
 <li>Bạn có thể thấy rằng tóm tắt mới nhất của tôi 192.168.0.0 / 16 không ghi đè lên bản tóm tắt cũ. Bạn phải tự loại bỏ cái cũ.</li>
 </ul>

 - Vậy điều gì xảy ra khi chúng ta gửi một ping đến một địa chỉ IP trong không gian địa chỉ 192.168.0.0/16 nhưng không được cấu hình trên bất kỳ giao diện nào?

 ![](https://i.imgur.com/NvTbZIR.png)

 - Như bạn thấy, router Jack nói với chúng tôi thông qua ICMP rằng địa chỉ IP này không thể truy cập (unreachable.).
 ![](https://i.imgur.com/cVMKesK.png)

 - Hãy chuyển qua router Jack và thực hiện một debuger. Debug gói ip là RẤT hữu ích nhưng bạn cần phải sử dụng một access-list nếu không bạn bị ngập  trong thông tin (thông tin đổ về quá nhiều ).

 ![](https://i.imgur.com/8AjxCVJ.png)

 - Chúng ta hãy gửi lại các ping đó ...

 ![](https://i.imgur.com/thc3tNG.png)

 - Những gói dữ liệu được in đậm đi mà không có gói tin đã đi trước ... chỉ có thời gian này không có thế giới mới lạ để khám phá ... .những gói dữ liệu đã biến mất mãi mãi!

 - Tại sao EIGRP hoạt động như thế này? Có một lý do rất tốt. Điều gì xảy ra nếu router thứ 3 trong topology và router của chúng ta có một tuyến đường mặc định trỏ tới router này? Chúng ta sẽ kết thúc việc chuyển tiếp gói tin cho 192.168.200.20 tới tuyến mặc định với cơ hội tạo ra một vòng lặp định tuyến.

 ![](https://i.imgur.com/CHbQx9o.png)

 - Chúng ta hãy làm quen với mô hình của chúng ta để xem lý do tại sao chúng ta cần có giao diện Null0 này. Router John có một interface kết nối với Internet. Router John có default route đến Internet.

 - Vì chúng ta muốn truy cập Internet trên router Jack, chúng ta sẽ cấu hình một tuyến đường mặc định trên router Jack tới router John.
 ![](https://i.imgur.com/ivXdjfP.png)

 - Đây là những gì các tuyến đường mặc định trên router Jack trỏ đến John trông giống như vậy. 
 ![](https://i.imgur.com/MHkskLD.png)

 - Đây là những gì sẽ xảy ra nếu chúng ta không có interface Null0:
 <ul>
 <li>1. Router John có tóm tắt 192.168.0.0 / 22 trong bảng định tuyến của nó.</li>
 <li>2. Router John sends an IP packet to 192.168.200.20 and forwards it to router Jack</li>
 <li>3. Router Jack không có mạng 192.168.200.X trong bảng định tuyến nhưng nó lại có một tuyến đường mặc định.</li>
 <li>4. Router Jack sẽ chuyển gói IP tới router John.</li>
 <li>5. Uh-oh ... chúng ta có một vòng lặp định tuyến!</li>
 </ul>

 - Các gói tin IP có một trường TTL (Time to live) để chúng không bị trả lại mãi mãi nhưng nó không phải là một điều tốt. Nhờ interface Null0 của chúng ta, điều này sẽ không xảy ra, hãy theo dõi điều này:
 ![](https://i.imgur.com/lEzSwEd.png)
 
 - Chúng tôi đang gửi một ping khác từ router John tới router Jack.
 ![](https://i.imgur.com/VA5lvkH.png)

 - Router Jack sẽ tra cứu trong bảng định tuyến của nó để xem nếu có gì phù hợp với 192.168.200.20. Mục nhập của chúng với 192.168.0.0/22 là cụ thể hơn so với 0.0.0.0/0 vì vậy đó là một trong những gì chúng ta sẽ sử dụng. Các gói tin sẽ được chuyển tiếp đến Null0 và đã biến mất! Không có thêm việc lặp định tuyến ...

 - Tóm tắt tạo ra có một lợi thế hơn nữa ngoài việc giảm kích thước của bảng định tuyến. Bạn cũng sẽ có ít bản cập nhật định tuyến trên mạng của mình.

 ![](https://i.imgur.com/5k8UkVR.png)

 - Xem topo ở trên. Chúng tôi đang chạy EIGRP trên tất cả các router. router ở phía bên trái có một interface đang down.

 ![](https://i.imgur.com/kWwRyOZ.png)

 - Router của chúng tôi sẽ gửi một bản cập nhật cho EIGRP hàng xóm của nó cái sẽ đưa qua nó cùng với các router khác chạy EIGRP. Toàn bộ mạng đang cập nhật chính nó bởi vì chỉ có một giao diện đơn lẻ đã đi down. Tóm tắt có thể giúp chúng ta ở đây.

 ![](https://i.imgur.com/18GWHaO.png)

 - Nếu chúng ta có một bản tóm tắt được cấu hình trên router bên trái để EIGRP hàng xóm của nó không có gì sẽ xảy ra ngay khi giao diện của nó bị down. Tất cả các router ở phía bên phải có 172.16.0.0 / 16 trong bảng định tuyến của họ và đó là nó. 

 - Tôi có thể cho bạn biết gì về tóm tắt trong EIGRP?
 <ul>
 <li>Ngay khi bạn xóa tuyến đường cuối cùng của bản tóm tắt, bản tóm tắt của bạn sẽ bị xóa khỏi bảng định tuyến.</li>
 <li>metric thấp nhất bạn có cho một tuyến đường cụ thể sẽ được sử dụng cho tuyến đường tóm lược</li>
 <li>Nếu bạn muốn bạn có thể chỉ định một AD khác nhau (administrative distance) cho bản tóm tắt của bạn.</li>
 </ul>

 - Đó là tất cả những gì tôi có cho bạn trong tóm tắt EIGRP! Bạn có thích điều này không? Chúng tôi vẫn còn một vài chương EIGRP còn lại!

 - Nếu bạn muốn xem tóm tắt EIGRP trong hoạt động thực tế, bạn nên xem xét các bài lab sau:

 [link 1](http://gns3vault.com/EIGRP/eigrp-auto-summarization.html)
 [link 2](http://gns3vault.com/EIGRP/eigrp-summarization.html)




 <a name="4"></a>
_______________________________

## 4. EIGRP over Frame-Relay

 - Nếu bạn đã học CCNA, bạn đã thấy frame relay và các khái niệm sau đây nên gọi cho bạn một hồi chuông:
 <ul>
 <li>NBMA (mạng không dây phát sóng đa truy cập - Non broadcast multi-access network)</li>
 <li>Nghịch đảo ARP</li>
 <li>Điểm đến điểm và điểm-đa điểm</li>
 <li>vấn đề liên quan đến Split-horizon</li>
 </ul>

 - Frame-relay là một trong những chủ đề mà bạn có thể không gặp phải trong thực tế cuộc sống thường xuyên nhưng vẫn còn nhiều kiểm tra trên các kỳ thi của Cisco. Đối với những người mới biết đến frame relay hoặc một chút mờ về đề tài này tôi sẽ bắt đầu với một cái nhìn tổng quan.

![](https://i.imgur.com/yy5FxG3.png)

 - Đây là hình ảnh của frame-relay. Ý tưởng đằng sau frame-relay là bạn có một cơ sở hạ tầng duy nhất từ nhà cung cấp dịch vụ và nhiều khách hàng được kết nối với nó, chia sẻ mọi thứ một cách có hiệu quả

 - Ở giữa bạn thấy một đám mây với một biểu tượng. Biểu tượng này là công tắc chuyển tiếp khung. Đám mây được gọi là *frame-relay cloud** và lý do nó có tên này là bởi vì đối với chúng tôi như là khách hàng, nó không biết những gì xảy ra trong đám mây chuyển tiếp khung. Đây là cơ sở hạ tầng của nhà cung cấp dịch vụ và chúng tôi thực sự không quan tâm những gì xảy ra ở đó ... chúng tôi là khách hàng và tất cả những gì chúng tôi muốn là kết nối!

 - Bạn thấy gì khác? Có hai khách hàng (A và B) và mỗi người đều có trụ sở chính (HQ) và văn phòng chi nhánh

![](https://i.imgur.com/8ETSGRL.png)

 - Một hình ảnh nữa, đây là một mạng lưới frame-relay với ba router từ một công ty. Có một bộ định tuyến tại trụ sở chính và chúng tôi có hai văn phòng chi nhánh. Tất cả đều được kết nối với đám mây frame-relay.

![](https://i.imgur.com/ZSHn5Fu.png)

 - Chúng tôi gọi nhà cung cấp dịch vụ của chúng tôi vì chúng tôi muốn kết nối và câu hỏi đầu tiên mà họ sẽ hỏi chúng tôi là nên kết nối các vị trí nào? Trong ví dụ trên, bạn có thể thấy **hai mạch ảo**, một màu đỏ và màu xanh. Với frame relay thì có một sự khác biệt giữa các kết nối vật lý và logic. Kết nối vật lý chỉ là cáp nối tiếp được kết nối với nhà cung cấp. Liên kết hợp lý của chúng tôi là các mạch ảo. Như bạn thấy, có một mạch ảo từ văn phòng chi nhánh 1 đến bộ định tuyến HQ và một bộ định tuyến khác từ văn phòng chi nhánh 2 đến bộ định tuyến HQ.

 - Điều này có nghĩa là chúng ta có thể gửi lưu lượng thông qua các mạch ảo giữa:
 <ul>
 <li>chi nhánh 1 và trụ sở chính </li>
 <li>chi nhánh 2 và trụ sử chính </li>
 </ul>

 - Không có mạch ảo giữa chi nhánh 1 và chi nhánh 2. Điều này có nghĩa là không có kết nối giữa chúng? Không, bạn vẫn có thể kết nối giữa chúng bằng cách gửi dữ liệu đến router HQ! Tất nhiên bạn có thể có được một mạch ảo giữa chi nhánh 1 và chi nhánh 2 nhưng bạn sẽ phải trả tiền cho nó. Các mạch ảo cũng được gọi là **PVC (Mạch ảo Vĩnh viễn- Permanent Virtual Circuit)**

 - Bạn cũng phải trả cho một tốc độ nhất định gọi là **CIR (Committed Information Rate)**. Điều tốt về frame-relay là khi không có khách hàng khác đang sử dụng mạng frame-relay có thể bạn nhận được một tốc độ cao hơn những gì bạn trả tiền cho ... CIR tuy nhiên là một tốc độ được đảm bảo. Làm thế nào để chúng ta biết được một PVC đang làm việc hay không?

 ![](https://i.imgur.com/e53qGjo.png)

 - Frame-relay sử dụng cái gì đó gọi là **LMI** là viết tắt của **Local Management Interface**. LMI có hai chức năng
 <ul>
 <li>Đó là một cơ chế giữ</li>
 <li>Nó cho chúng ta biết PVC có hoạt động hay không hoạt động</li>
 <li>Nó cũng cho chúng ta một **DLCI (Data Link Connection Identifier)**. Tôi sẽ nói về điều này một chút</li>
 </ul>

 - đó là 3 loiạ của LMI . Tất cả đều làm tương tự nhưng có ba tiêu chuẩn không tương thích với nhau. Bất cứ điều gì bạn chọn hãy chắc chắn rằng nó giống nhau giữa hai thiết bị đầu cuối . có nghĩa là nếu bạn chọn ở trụ sở chính là cisco thì ở chi nhánh bạn củng phải sử dụng thiết bị của cisco và ngược lại.

 ![](https://i.imgur.com/e53qGjo.png)

 - Dưới đây là một ví dụ về LMI đang hoạt động. Ở giữa chúng tôi có một switch frame-relay. Các gói tin LMI được gửi giữa Router A , bộ chuyển mạch frame-relay và router B . Bộ chuyển mạch frame relay cho các bộ định tuyến biết rằng PVC đang hoạt động.

 - Bạn cần biết gì về frame relay? Hãy để tôi ném mô hình OSI vào bạn:

![](https://i.imgur.com/mjvR4i0.png)

 - Các giao thức WAN mô tả lớp vật lý (lớp 1) và lớp liên kết dữ liệu (lớp 2). Frame-relay sử dụng gì trên lớp liên kết dữ liệu ? Chúng ta không sử dụng địa chỉ MAC vì đó là Ethernet nhưng chúng ta có cái gì khác gọi là **DLCI (Data Link Connection Identifier)**.

 ![](https://i.imgur.com/EZ9nRXF.png)

 - Đối với mỗi PVC, bạn sẽ nhận được một DLCI cho mỗi bộ định tuyến. Trong ví dụ trên, bạn có thể thấy rằng đối với PVC giữa router HQ và văn phòng chi nhánh 1, chúng tôi có DLCI 102 trên router HQ và DLCI 201 trên router nhánh văn phòng 1. Giữa router HQ và văn phòng chi nhánh 2 chúng tôi có DLCI 103 trên HQ và DLCI 301 trên văn phòng chi nhánh 2. DLCI của chúng tôi không có ý nghĩa gì khác hơn là một định danh duy nhất cho lớp liên kết dữ liệu trên mỗi PVC.

 - Bây giờ có một khái niệm quan trọng để nắm bắt và ghi nhớ về DLCI. DLCI chỉ được ** địa phương biết đến ** trên router! Router của bạn ** không biết ** DLCI của router ở phía bên kia. Điều này khác nếu bạn so sánh nó với Ethernet. Trong thế giới Ethernet của chúng ta bạn cần phải biết địa chỉ MAC của máy tính ở phía bên kia để gửi một cái gì đó đến nó.

 - Điều này cũng giống như đi tàu hỏa. Nếu bạn đang ở ga tàu bạn đi bộ đến ga tàu lửa chính xác và lên tàu. Bạn không có ý tưởng về sân ga xe lửa mà bạn sẽ đến và bạn củng không quan tâm.

 - Frame-relay hỗ trợ nhiều topo
 <ul>
 <li> Full-mesh</li>
 <li> Partial-mesh</li>
 <li> Hub and Spoke</li>
 </ul>
![](https://i.imgur.com/DbX5itw.png)

 - Đây là topo full-mesh của chúng ta. Như bạn thấy, có một PVC giữa mỗi router.

![](https://i.imgur.com/FsLqQw2.png)

 - Đây là một  partial-mesh . Các router quan trọng hơn sẽ có nhiều kết nối với những người khác.
![](https://i.imgur.com/exosvFP.png)

 - còn đây là dạng hub and spoke. Bộ định tuyến ở bên trái là trung tâm của chúng tôi và các bộ định tuyến khác là các bộ đàm. Nếu các bộ đàm muốn liên lạc với nhau, họ sẽ phải gửi lưu lượng tới router trung tâm.

### Frame-relay is **NBMA (non-broadcast multi-access)**


 -Giữ nó trong tâm trí. Điều này có nghĩa là frame-relay là đa truy cập vì tất cả các router có thể truy cập vào mạng nhưng bạn không thể gửi broadcasts qua mạng frame-relay. Không phát sóng cũng có nghĩa là bạn không thể gửi lưu lượng multicast. Không có multicast có nghĩa là bạn sẽ gặp rắc rối với các giao thức định tuyến. Rip phiên bản 2, OSPF và EIGRP đều sử dụng multicast. Điều này có nghĩa là bạn không thể sử dụng các giao thức định tuyến với frame relay? có thể không, nhưng nó cần một chút khôn lanh: 
 <ul>
 <li>RIP, OSPF và EIGRP cũng có thể sử dụng unicast thay vì multicast</li>
 <li>Có một phương pháp để "mô phỏng" lưu lượng broadcasts qua mạng frame-relay của bạn</li>
 </ul>
 ![](https://i.imgur.com/9nWFUKA.png)

 - Chúng ta có thể gặp phải những vấn đề gì khác với frame relay và routing? Bạn có nhớ các đặc tính của các giao thức định tuyến distance vector (RIP và EIGRP)? Split-horizon ?

 - Trong hình trên, tôi đã cấu hình EIGRP trên tất cả các bộ định tuyến. Văn phòng chi nhánh của Router 1 đang gửi thông tin định tuyến đến bộ router customer HQ. Nếu chúng ta nhìn vào bảng định tuyến, chúng ta sẽ thấy thông tin định tuyến này trên router HQ.

 ![](https://i.imgur.com/COItiwd.png)

 - Bạn có nhớ luậtsplip-horizon không? Bất kể bạn học từ người hàng xóm của bạn, bạn không quảng cáo lại cho họ. Để cụ thể hơn:** bất cứ điều gì bạn học trên một giao diện bạn không quảng cáo nó trở lại trên cùng một giao diện**.

 - Chúng tôi đang sử dụng hai PVC nhưng trên router HQ vẫn còn chỉ có một giao diện vật lý. Splithorizon sẽ ngăn không cho quảng cáo thông tin định tuyến đến văn phòng chi nhánh của router 2.

 - Làm thế nào chúng ta có thể giải quyết vấn đề này?
 <ul>
 <li>chúng ta có thể tắt split-horizon ( được bật mặc định trên các cổng vật lý)</li>
 <li>chúng ta có thể sử dụng sub-interface</li>
 </ul>

 ![](https://i.imgur.com/VPanOk7.png)

 - Nếu bạn sử dụng một giao diện con bạn không có vấn đề split-horizon vì bạn đang học các thông tin định tuyến trên serial0 / 0.1 và quảng cáo nó ra khỏi serial0 / 0.2

 - Frame-relay có thể sử dụng giao diện phụ **điểm-điểm** hoặc các giao diện phụ **điểm-đa-điểm**. Nếu bạn sử dụng point-to-point, nó sẽ giải quyết vấn đề split-horizon của bạn nhưng bạn sẽ cần sử dụng một subnet IP khác nhau cho mỗi PVC. Point-to-multipoint có nghĩa là bạn có vấn đề về split-horizon nhưng bạn có thể sử dụng một subnet IP cho tất cả các PVCs.

 - Nhớ ARP (giao thức giải quyết địa chỉ)? Khi chúng ta sử dụng ARP cho Ethernet, chúng ta cần phải tìm hiểu địa chỉ MAC của máy tính mà chúng ta muốn gửi đi. ARP có hiệu quả bản đồ địa chỉ IP đích đến địa chỉ MAC đích.

 - Frame-relay sử dụng **ARP ngược** và hơi khác một chút. Hãy nhớ câu chuyện của tôi về nền tảng xe lửa và cách mà bộ định tuyến của bạn chỉ biết rằng đó là DLCI địa phương? Bạn không biết DLCI ở phía bên kia

 - Inverse ARP sẽ lập bản đồ DLCI **địa phương của bạn tới địa chỉ IP của phía bên kia**:

 ![]9https://i.imgur.com/j4Sjzka.png

 - Router Frodo trong ví dụ trên của tôi đã vẽ bản đồ địa chỉ IP của router Gandalf (192.16.12.2) tới DLCI 102 địa phương của nó. Đó là ARP nghịch đảo. Hãy xem chi tiết hơn: 

 ![](https://i.imgur.com/j4Sjzka.png)

 - khi chúng ta cấu hình frame-relay thì chuyện gì sẽ xảy ra ?

 - 1. Router của chúng tôi sẽ thực hiện điều tra tình trạng sử dụng LMI.
 - 2. Chuyển đổi frame-relay sẽ cho chúng ta số DLCI của chúng ta (hoặc bạn có thể tự cấu hình nó).

 ![](https://i.imgur.com/ICNSjWr.png)

 - Một khi các bộ định tuyến của chúng tôi biết PVC hoạt động, họ sẽ gửi một tin nhắn hello với địa chỉ IP của họ. Trong ví dụ của tôi, bạn chỉ thấy router Frodo gửi đi nhưng tất nhiên router Gandalf cũng sẽ gửi về địa chỉ IP của nó.

 ![](https://i.imgur.com/KA1VmrM.png)

 - Router Frodo bây giờ sẽ biết nó có thể đạt đến địa chỉ IP 192.168.12.2 bằng cách gửi lưu lượng thông qua PVC với DLCI 102. Router Gandalf sẽ biết rằng nó có thể đạt được địa chỉ IP 192.168.12.1 thông qua PVC với DLCI 201.

 - Tôi hy vọng điều này làm mới lại kiến thức frame relay của bạn bây giờ tôi sẽ giới thiệu cho bạn các cách khác nhau trong việc định cấu hình EIGRP qua mạng chuyển tiếp frame-relay của bạn

 ![](https://i.imgur.com/Uk1MIdB.png)

 - Topology ở trên là mô hình mà tôi sẽ sử dụng để chỉ cho bạn cách chạy EIGRP quamạng chuyển tiếp khung. Ở phía bên trái chúng ta có một router hub và bên phải là 2 router spoke. Đây là một ví dụ điển hình của một mô hình hub and spoke và lý tưởng cho một bài lab

 ![](https://i.imgur.com/BCeh4iQ.png)

 - Cùng một topo nhưng tôi đã thêm vào subnet 192.168.123.0 / 24. Như bạn thấy, bộ định tuyến Hub của chúng tôi có địa chỉ IP1, Spoke1 có 0,2 và Spoke2 có 0,3.

 - Vì chúng ta đang sử dụng một subnet IP duy nhất, chúng ta đang sử dụng frame-relay point-to-multipoint. Hãy nhớ rằng với frame-relay giao diện vật lý là điểm-đa-điểm theo mặc định!

![](https://i.imgur.com/ug33jjD.png)

![](https://i.imgur.com/fPY4QKZ.png)

 - Đây là cấu hình của các giao diện của ba router. Chỉ cần cấu hình frame-relay điểm-đa điểm.

![](https://i.imgur.com/gr6LjqW.png)

 - Đây là cấu hình EIGRP của các bộ định tuyến của chúng tôi. Không phải là khó khăn phải không? Các lệnh bộ định tuyến cơ bản của EIGRP và bạn phải thay đổi giao diện nối tiếp sang frame-relay encapsulation.

![](https://i.imgur.com/neZZmnE.png)

 - chúng ta có thể EIGRP adjacency đã được thiết lập

![](https://i.imgur.com/wOY4gFS.png)

 - Hãy nhìn vào đầu ra của lệnh **show frame-relay map** trên router hub. Inverse ARP được bật theo mặc định, đó là lý do tại sao bạn nhìn thấy từ **dynamic** trong các ánh xạ framerelay. Chúng ta thấy rằng nó đã học được về các địa chỉ IP của bộ định tuyến đã nói và các số DLCI cục bộ nào chúng ta phải lập bản đồ.

 - Có 3 điều quan trọng cần học trong đầu ra ở trên:
 <ul>
 <li>Chúng tôi đã không định cấu hình bất kỳ frame-relay mappings nào có nghĩa là Inverse ARP được bật theo mặc định.</li>
 <li>Từ **dynamic** có nghĩa là chúng ta đang sử dụng Inverse ARP.</li>
 <li>Việc gửi **từ khóabroadcast** có nghĩa là lưu lượng truy cập broadcast giả lập để chúng tôi có thể sử dụng multicast nữa. Inverse ARP đã bật tính năng này cho chúng tôi.</li>
 </ul>

 - Hãy vô hiệu hóa Inverse ARP trên bộ định tuyến trung tâm và tự cấu hình một số ánh xạ frame-relay:

 ![](https://i.imgur.com/ZYdZb4o.png)

 - Đó là tất cả ta có. Gõ vào **no frame-relay inverse-arp** trong giao diện và bạn sẽ vô hiệu hóa ARP nghịch đảo.

 ![](https://i.imgur.com/VxwwGJE.png)

 - Đừng quên gỡ bỏ các ánh xạ frame-relay trước khi học bằng cách sử dụng lệnh **clearing framerelay inarp** .

 - Bước tiếp theo là cấu hình bản đồ hóa frame-relay:

 ![](https://i.imgur.com/tSCwOrQ.png)

 - Bạn cấu hình nó ở mục interface bằng cách sử dụng lệnh **frame-relay map** . Bạn phải chỉ định từ khoá **broadcast** hoặc mạng frame-relay của bạn sẽ chỉ hỗ trợ unicast! Vì EIGRP sử dụng multicast, bạn sẽ gặp rắc rối nếu bạn quên sử dụng chúng.

 - Chúng ta có thể làm gì khác với EIGRP và frame relay? Chúng ta hãy quên đi giao diện vật lý và chuyển các lệnh frame-relay đến một giao diện con!

 ![](https://i.imgur.com/dhKzFGM.png)

 - Tôi sẽ di chuyển địa chỉ IP và các frame-relay mapping từ giao diện vật lý đến một subinterface. 

 ![](https://i.imgur.com/y1ylRUb.png)

 ![](https://i.imgur.com/pmWng9i.png)

 - Dưới đây là tổng quan về interface physical và subinterface.

 - Chỉ có hai điều tôi để lại trên giao diện vật lý:
 <ul>
 <li>Kiểu đóng gói, chúng ta muốn chạy frame relay đúng không?</li>
 <li>Vô hiệu hoá ARP nghịch đảo với lệnh no frame-relay inverse-arp </li>
 </ul>

 - Chúng tôi không muốn bất kỳ mappings frame-relay nào trên giao diện vật lý vì chúng ta cần chúng trên giao diện phụ. Nếu bạn tạo ra một giao diện phụ, bạn cần chỉ định xem đó là đa điểm hay điểm-điểm. Tôi vẫn đang sử dụng một subnet IP cho tất cả các router vì vậy chúng ta đang sử dụng multipoint trong tình huống này.
 ![](https://i.imgur.com/yFnQ4qd.png)

 - Đây là một bước quan trọng mà bạn không nên quên. Trên giao diện vật lý split-horizon bị **vô hiệu** nhưng trên giao diện phụ được **kích hoạt** mặc định! Đừng quên thêm bản đồ framerelay của bạn trên giao diện phụ với từ khoá broadcast ở cuối.

 ![](https://i.imgur.com/4wU35KW.png)

 - bạn có thể thấy tin nhắn nhanh rằng split-horizon đã thay đổi.

 - điều gì sẽ xảy ra nếu tôi quên gõ từ khóa broadcast ở cuối câu lệnh thiết lập , nó sẽ trông như ví dụ này :

 ![](https://i.imgur.com/n83EYp3.png)

 - Cấu hình frame-relay của chúng tôi không hỗ trợ broadcast hay multicast nữa ... chỉ unicast.

 ![](https://i.imgur.com/lL9oUuy.png)

 - sau một khoảng thời gian ngắn bạn sẽ thấy tin nhắn như thế này.

 - vẫn còn nhiều phương pháp để  EIGRP làm việc? Chắc chắn có! Chỉ cần sử dụng lệnh neighbor. Nếu bạn chỉ định các** hàng xóm **EIGRP theo cách thủ công, chúng tôi sẽ chuyển sang unicast.

 ![](https://i.imgur.com/H7eiPn9.png)

 - chúng ta đi nào ... chỉ định các hàng xóm EIGRP và chúng ta không cần multicast nữa và bạn có thể quên về từ khóa broadcast trong các mapping frame-relay của bạn. Đó là tất cả các tùy chọn chúng ta có để chạy EIGRP qua frame relay bằng cách sử dụng interface physical hoặc subinterface **multipoint**.

 - Tôi vẫn cần cho bạn thấy phương pháp interface point-to-point. 

 ![](https://i.imgur.com/eoENrds.png)

 - Chúng tôi đang sử dụng cùng một topo để chứng minh EIGRP điểm-tới-điểm qua frame-relay với một sự khác biệt. Các liên kết điểm đến điểm yêu cầu **một Subnet IP cho mỗi PVC:**
 - Hub and Spoke1: 192.168.12.0 /24
 - Hub and Spoke2: 192.168.13.0 /24

 ![](https://i.imgur.com/2NkoTwo.png)

 - Đây là cấu hình cho hub và router spoke. Bạn chỉ cần xác định encapsulation frame-relay trên giao diện vật lý. Phần còn lại của các lệnh được trên các giao diện phụ. Bộ định tuyến của bạn không thể đọc được tâm trí của bạn và tìm hiểu về những giao diện phụ nào mà DLCI nên có để bạn phải tự cấu hình nó. Chúng ta không sử dụng lệnh frame-relay map cho các giao diện phụ point-to-point nhưng bạn phải sử dụng câu lệnh **frame-relay interface-dlci**  ở đây.

 - Vì chúng ta đang sử dụng 2 sub-interface trên router hub  thay vì một interface miltipoint chúng tôi không phải đối phó với các vấn đề split-horizon ở đây!

 - Bây giờ bạn đã thấy tất cả các cách khác nhau của cấu hình EIGRP qua mạng frame-relay. Còn một điều nữa bạn phải hiểu khi chạy EIGRP qua mạng frame-relay và đây là về việc sử dụng băng thông.
 <ul>
 <li>Mặc định EIGRP có thể sử dụng đến **50% băng thông giao diện cho lưu lượng EIGRP**</li>
 <li>Phần trăm có thể thay đổi</li>
 <li>giao diện point - to - point </li>
   - Băng thông được **xử lý như giao diện T1 (1.544Mbit)**.</li>
   - Cấu hình băng thông chính mình để phản ánh đúng băng thông</li>
 <li>interface multipoint </li>
   <li>Băng thông trên giao diện vật lý được **chia cho số lượng hàng xóm.**</li>
  </ul>
 - vấn đề ở đây là gì? Giả sử nhà cung cấp frame-relay của bạn đã cung cấp cho bạn một PVC với một CIR là 64kbps. Giao diện điểm-điểm của bạn là mặc định được đối xử như T1 là 1.544Mbit. EIGRP có thể chiếm 50% băng thông ... .50% của 1,544Mbit là 768kbps và voila ... PVC của bạn bị tràn ngập gói tin EIGRP!

 - Bạn có thể giải quyết vấn đề này bằng cách thiết lập đúng băng thông sử dụng lệnh băng thông trên giao diện và / hoặc bằng cách thay đổi phần trăm mà EIGRP có thể sử dụng cho lưu lượng truy cập.

 ![](https://i.imgur.com/tLEJgfI.png)

 - Đây là cách bạn thay đổi băng thông trên giao diện phụ. Nếu bạn thay đổi băng thông trên giao diện vật lý, giao diện phụ của bạn sẽ **không kế thừa** băng thông! Bạn cần phải chỉ định nó trên mỗi giao diện con cho mình.

 ![](https://i.imgur.com/3eXH2pP.png)

 - bạn có thể thấy được băng thông đã được thay đổi khi sử dụng lệnh **show interface**

 ![](https://i.imgur.com/NcfXvmi.png)

 - bằng cách sử dụng câu lệnh **ip bandwidth-percent eigrp**  bạn có thể thay đổi phần trăm mà EIGRP sử dụng cho lưu lượng. trong ví dụ trên tôi set 25% cho EIGRP autonomous System 123. 

 - Tại sao tôi muốn thay đổi tỷ lệ này? Lưu ý rằng thay đổi băng thông cũng ảnh hưởng đến metric vì vậy nếu bạn thay đổi băng thông do chính sách định tuyến, bạn có thể không muốn thay đổi băng thông. Hãy tưởng tượng bạn có một liên kết FastEthernet nhưng thiết lập băng thông tới 64kbps nên giao diện không kém hấp dẫn đối với EIGRP. 50% 64kbps chỉ là 32kbps mà EIGRP cho phép sử dụng trên giao diện FastEthernet này ... điều đó không đúng sao? Đó là lý do tại sao bạn có thể đặt tỷ lệ phần trăm băng thông lên trên 100%.

 - Bạn vẫn đang đọc đấy chứ? Tốt! Chúng ta hãy cùng nhau đánh giá một số ví dụ điển hình với các vấn đề liên quan đến băng thông EIGRP.

 ![](https://i.imgur.com/J0YfSnC.png)

 - trong ví dụ trên tôi có 5 router trong mô hình HUB and spoke . router phía trên cùng là trung tâm và 4 router đóng vai trò phụ ở phía dưới. đối với mỗi spoke chúng đều có mỗi PVC và mỗi cái đều có một CIR khác nhau.

 -PVC 1:  CIR  128kbps
 -PVC 2:  CIR  128kbps
 -PVC 3:  CIR  256kbps
 -PVC 4:  CIR  64kbps
 
 - nếu chúng ta cấu hình mạng này thành point-to-point thì sẽ có một vấn đề. Điều gì sẽ xảy ra khi router spoke3 gửi bản cập nhật EIGRP ở mức 50% dung lượng của nó router spoke4?

 - 50% của 256kbps = 128kbps

 - PVC4 chỉ có một CIR 64kbps nên nó sẽ bị quá tải với lưu lượng EIGRP ... đây không phải là một ý tưởng hay.

 - Làm thế nào chúng ta có thể khắc phục điều này? Phương pháp tốt nhất là loại bỏ cài đặt đa điểm và sử dụng các subinterface point-to-pointvì nó cho phép bạn thiết lập băng thông cho mỗi subinterface và do đó cho mỗi hàng xóm. Chúng ta sẽ có một giải pháp dễ dàng.

 - nếu bạn vẫn muốn giữ ở chế độ multipoint thì những gì bạn phải làm là :
 <ul>
 <li>Lấy PVC với CIR thấp nhất. Trong ví dụ của chúng tôi, đây là PVC4 với một CIR là 64kbps.</li>
 <li>Nhân 64kbps với số lượng PVCs và cấu hình này như là băng thông trên router hub</li>
 </ul>

 ![](https://i.imgur.com/KLHtTpn.png)

 - Nếu bạn sử dụng các giao diện đa điểm EIGRP sẽ chia băng thông cho số lượng người hàng xóm. Trong ví dụ của chúng tôi điều này có nghĩa là mỗi PVC sẽ nhận được 64kbps đó là băng thông của băng thông thấp nhất PVC. 
 
 - Giải pháp này sẽ không nhận được tối đa các PVCs với CIR cao hơn nhưng sẽ đảm bảo rằng PVC CIR thấp hơn không bị quá tải với lưu lượng truy cập.

 - hãy xem một mô hình khác 

![](https://i.imgur.com/ekAhDgb.png)

 - ở mô hình trên tôi có 1 router trung tâm và 10 router phụ .tất cả PVC đều được cấu hình point-to-point và có CIR là 64kbps. cổng vật lý trên router trung tâm có băng thông là 256kbps và được cấu hình chính xác.

 ![](https://i.imgur.com/pNBvKYJ.png)

 - đây là một phần cấu hình của router Hub . tôi chỉ hiển thị 3 router phụ đầu tiên. như chúng ta có thể thấy bandwidth được cấu hình đúng trên cổng vật lý là 256kbps . mỗi PVC được cấu hình với một point-to-point  subinterface.

 - Điều gì sẽ xảy ra khi router Hub của chúng tôi cố gắng liên lạc với tất cả các router đã nói cùng một lúc với dung lượng đầy đủ? 10x 64kbps là 640kbps và cổng vật lý của chúng tôi không chạy nhanh hơn 256kbps ... chúng tôi sẽ hết dung lượng! Chúng ta phải thực hiện một số thay đổi để giải quyết vấn đề này.

 ![](https://i.imgur.com/rzpXlir.png)

 - chúng ta sẽ bắt đầu với router Hub. Băng thông vật lý của giao diện là 256kbps và vì chúng ta có 10 PVC băng thông này sẽ được chia tự động giữa các PVC, không cần phải định cấu hình băng thông theo cách **thủ công** trên mỗi point-to-point sub-interface.

 - 256 / 10 = 25kbps cho mỗi PVC.

 - Mỗi PVC có băng thông 64kbps tuy nhiên vì vậy chúng ta cần phải làm gì đó để đảm bảo rằng EIGRP vẫn có thể sử dụng 50% băng thông có sẵn. 

 - Tôi đã thay đổi tỷ lệ% EIGRP AS 123 có thể sử dụng đến 128%. 128% của 25kbps = 32kbps

 - 32kbps chính xác là 50% tỷ lệ CIR hiện có cho mỗi PVC.

 - còn router spoke thì sao? Chúng ta cần phải thay đổi cấu hình của chúng để chúng tương thích router hub. Để tôi chỉ cho bạn một trong số họ:
 ![](https://i.imgur.com/YKNIL93.png)

 - chúng ta set bandwidth là 25 và % sử dụng cho EIGRP là 128% cho AS 123

 - 128% của 25kbps = 32kbps

 - 32kbps chính xác là 50% tỷ lệ CIR hiện có của PVC của chúng ta.

 - giải pháp này co một nhược điểm. Vì EIGRP chia băng thông của các giao diện nhiều điểm tự động qua số hàng xóm nên không nên có bất kỳ sự thay đổi về số lượng hàng xóm của EIGRP hoặc nếu không tính toán của chúng ta là không chính xác.

 - Bây giờ bạn đã thấy giải pháp đa điểm và điểm-điểm, nhưng cũng có một lựa chọn **lai**. Chúng ta sẽ kết hợp các giao diện đa điểm và điểm-tới-điểm cho một giao diện này!

 ![](https://i.imgur.com/xLu3zeW.png)

 - trong ví dụ trên chúng ta có mô hình giống với ví dụ đầu tiên , có 1 router hub ở trên đỉnh và 4 router spoke bên dưới. Có một cái gì đó khác với CIR của PVC của chúng ta trước đây:
    PVC 1,2 and 3: CIR 256kbps
    PVC 4: CIR 128kbps

 - Vì vậy PVC 1, 2 và 3 có cùng tốc độ CIR là 256kbps trong khi đó PVC4 chậm hơn ở tốc độ 128kbps. Chúng ta có thể kết hợp 3 PVC với CIRC 256kbps trên giao diện đa điểm trong khi PVC chậm được cấu hình trên một giao diện điểm tới điểm riêng biệt.

 ![](https://i.imgur.com/ZzQxCtF.png)

 - Đây là những gì chúng ta phải làm trên router hub. PVC1, 2 và 3 chúng ta sẽ cấu hình theo subinterface multipoint và cho nó một băng thông 768kbps. EIGRP tự động chia băng thông qua số lượng hàng xóm của EIGRP nên mỗi máy sẽ được 256kbps phù hợp với tốc độ CIR là 256kbps.

 - Số 4 có PVC chậm hơn sẽ được cấu hình dưới dạng một điểm giao diện điểm tới điểm riêng biệt, nơi chúng tôi đặt đúng băng thông. 

 - Chúng tôi đã đưa bạn đến cuối chương này. Tôi tin rằng EIGRP với frame-relay và các cấu hình băng thông / CIR khác nhau có lẽ là phần khó nhất để hiểu về chủ đề này. Nếu bạn muốn một số thực hành tốt hãy kiểm tra các bài lab frame-relay tôi tạo ra cho EIGRP

 - Nếu có không rõ điều gì trên frame relay, bạn có thể bắt đầu với phòng thí nghiệm này:
 
 [lab 1](http://gns3vault.com/Frame-Relay/frame-relay-basics.html)

 - Ngừng lại và tiếp theo là cấu hình EIGRP qua frame-relay:

 [lab 2](http://gns3vault.com/EIGRP/eigrp-over-frame-relay-with-sub-interfaces.html)
 [lab 3](http://gns3vault.com/EIGRP/eigrp-over-frame-relay-with-multipoint-interface.html)

 - Một khi bạn đã quen thuộc với EIGRP qua frame-relay, bạn có thể làm việc trên các phòng thí nghiệm khác nhau về tốc độ băng thông:

 [lab 4](http://gns3vault.com/EIGRP/eigrp-multipoint-bandwidth-pacing.html)
 [lab 5](http://gns3vault.com/EIGRP/eigrp-point-to-point-bandwidth-pacing.html)
 [lab 6](http://gns3vault.com/EIGRP/eigrp-hybrid-bandwidth-pacing.html)

----------------------------------------------
 <a name="5"</a>

## 5. Authentication EIGRP

 - Các giao thức định tuyến có thể được cấu hình để ngăn chặn việc nhận các bản cập nhật định tuyến sai và EIGRP không là ngoại lệ . Nếu bạn không sử dụng xác thực và bạn đang chạy EIGRP ai đó có thể cố gắng tạo một neighbor adjacency EIGRP với một trong những bộ định tuyến của bạn và cố gắng gây rối với mạng của bạn ... chúng tôi không muốn điều đó xảy ra đúng không?

 - Chúng ta phải làm gì để xac thực trong EIGRP? ** MD5 ** nó là cách chúng ta sẽ làm.

 - EIGRP chỉ cung cấp xác thực MD5, không có chứng thực bản rõ. chứng thực cung cấp điều gì .
 <ul>
 <li>Bộ định tuyến của bạn sẽ xác thực nguồn của mỗi gói cập nhật định tuyến mà nó sẽ nhận được.</li>
 <li>Ngăn chặn cập nhật định tuyến sai từ các nguồn không được chấp thuận.</li>
 <li>Bỏ qua các bản cập nhật định tuyến độc hại.</li>
 </ul>

 - Một hacker tiềm năng có thể đang ngồi trên mạng của bạn với một máy tính xách tay chạy GNS3 / Dynamips, khởi động một router Cisco và thử cố những điều sau:
 <ul>
 <li>Hãy cố gắng thiết lập mối quan hệ láng giềng với một trong những bộ định tuyến của bạn và quảng bá các tuyến đường rác.</li>
 <li>Gửi các gói tin độc hại và xem bạn có thể xóa bỏ hàng xóm láng giềng của một trong những bộ định tuyến được ủy quyền của bạn.</li>
 </ul>

 - để cấu hình xác thực EIGRP chúng ta cần làm những điều sau:

 - cấu hình key-chain. 
 - cấu hình key ID ở dưới key-chain
 <ul>
 <li>chỉ định mật khẩu cho key ID </li>
 <li>Tùy chọn: xác định chấp nhận và thời gian hết hạn của khoá.</li>
 </ul>

 ![](https://i.imgur.com/u2yiV9d.png)

 - Tôi sẽ sử dụng router Jack và John một lần nữa và lần này chúng ta sẽ cấu hình xác thực MD5 cho EIGRP. cấu hình cơ bản cho 2 router.

 ![](https://i.imgur.com/mNikgqG.png)

 - Chúng tôi sẽ bắt đầu bằng cách chỉ định một keychain. Tôi gọi là "KingKong" nhưng nó có thể khác nhau trên cả hai bộ định tuyến, nó không quan trọng. key ID là một giá trị phải khớp trên cả hai bộ định tuyến và key-string là mật khẩu phải khớp với key-id.

 ![](https://i.imgur.com/ElW2kWz.png)

 - Đầu tiên bạn phải tạo keychain và sau đó bạn cần phải kích hoạt nó trên interface. "12" là số AS của EIGRP. Cấu hình trên router John giống hệt vậy.

 ![](https://i.imgur.com/kO1f6NL.png)

 - Bạn có thể kiểm tra nếu cấu hình của bạn là chính xác bằng cách sử dụng câu lệnh **debug eigrp packets.** 

 - Bạn có thể thấy rằng chúng tôi đã nhận được một gói với xác thực MD5 nhưng tôi không cho phép xác thực MD5 trên router John. Hãy sửa nó:

 ![](https://i.imgur.com/iD0WV4G.png)

 - Ngay lập tức tôi có thể thấy rằng sự neighbor adjacency EIGRP đang làm việc:

 ![](https://i.imgur.com/ESe3EMC.png)

 - Điều gì sẽ xảy ra nếu tôi nhập sai chuỗi ký tự?

 ![](https://i.imgur.com/ExXHKja.png)

 - hãy xem nếu kingkong là apple thì chuyện gì xảy ra.

 ![](https://i.imgur.com/GCLTEfL.png)

 - Bạn sẽ thấy thông báo trên ở đầu ra gỡ lỗi trên router John. Ít nhất nó cho chúng ta biết rằng key 1 là một trong những lỗi.

 - Nếu bạn muốn thêm gia vị của nó lên một chút, bạn có thể thiết lập một chấp nhận và thời hạn sống trên các key. Ý tưởng đằng sau đó là bạn có thể có các key chỉ có giá trị trong một ngày, một tuần, một tháng hoặcthứ gì khác. Bạn có muốn sử dụng điều này trong cuộc sống thực không? Nó có thể tăng cường an ninh nhưng nó cũng làm cho việc bảo trì gặp một chút phức tạp hơn ...

 - Trước khi bạn cấu hình key với thời gian giới hạn, đảm bảo bạn đặt đúng thời gian và ngày. Bạn có thể làm điều này bằng tay trên mỗi router nhưng tốt hơn là sử dụng một máy chủ NTP (Network Time Protocol) vì vậy tất cả các bộ định tuyến có cùng thời gian / ngày.

 - Xem bạn có thể cấu hình xác thực với bài lab này :

 [Authentication 1](http://gns3vault.com/EIGRP/eigrp-authentication-rotating-key.html)

----------------------------

<a name="6"></a>

## 6. EIGRP Advanced Features

 - Đây là chương cuối cùng của EIGRP và chúng ta sẽ xem xét một số tính năng nâng cao của EIGRP. Chúng ta sẽ đi sâu hơn vào quá trình truy vấn EIGRP và các router stub có thể giúp chúng tôi giải quyết một số vấn đề như thế nào.
 - EIGRP được thiết kế cho các mạng doanh nghiệp lớn nhưng có một mạng EIGRP lớn (5000 + máy trạm và nhiều hop) có thể dẫn đến một số vấn đề:
 <ul>
 <li>Rất nhiều router EIGRP tương đương với một bảng topology lớn và bảng định tuyến. </li>
 <li>Tính toán router successor sẽ mất nhiều thời gian hơn nếu bạn có nhiều người hàng xóm của EIGRP và các đường dẫn khác nhau.</li>
 <li>Nếu có nhiều đường dẫn dự phòng EIGRP sẽ phải xem nếu có 1 hoặc nhiều feasible successor, thì việc này sẽ mất nhiều thời gian hơn.</li>
 <li>nhiều thông tin hơn có nghĩa là các router EIGRP sẽ phải làm việc nhiều hơn để xử lý</li>
 <li>Khi EIGRP mất tuyến và không có feasible successor thì tuyến đường sẽ chuyển từ **passive** sang **active** và router bắt đầu gửi các Queryes tới các nước láng giềng</li>
 <li>EIGRP gửi các truy vấn trên tất cả các interface ngoại trừ interface successor </li>
 </ul>

 - Chúng ta đã nói về summarization trước và làm thế nào để giảm kích thước của bảng định tuyến và dừng quy trình truy vấn. Để tôi mô tả chi tiết về quy trình truy vấn EIGRP cho bạn:

 ![](https://i.imgur.com/P8fzypu.png)

 - Trong topo trên, chúng ta đang chạy EIGRP trên tất cả các bộ định tuyến. Router 1 có một đường link bị lỗi và kết quả là đã mất tuyến đường chính tới một mạng lưới riêng ở phía bên trái. Không có feasible successor vì vậy tuyến đường đi từ **passive** sang **active** và chúng sẽ gửi một truy vấn tới router 2 và 3.

 - Có 2 điều có thể xảy ra vào lúc này:
 <ul>
 <li>Router 2 hoặc 3 có thông tin về tuyến đường cụ thể này và sẽ gửi thông tin về nó tới router 1. Quy trình truy vấn đã sẽ thúc.</li>
 <li>Router 2 hoặc 3 không biết bất cứ điều gì về tuyến đường này và sẽ gửi một truy vấn tới router lân cận router 4, 5 và router 6 và 7. Router 2 hoặc 3 sẽ không gửi trả lời cho router 1 cho đến khi họ nghe thấy một phản hồi từ tất cả hàng xóm của họ</li>
 </ul>

![](https://i.imgur.com/lsXpSAv.png)
 - Trong topology của chúng ta không ai có một đầu mối mà router mạng 1 đang tìm kiếm. Họ sẽ chuyển tiếp các truy vấn của họ tới các nước láng giềng của họ. Các mũi tên màu đỏ cho biết gói truy vấn

 ![](https://i.imgur.com/Q4yOwsS.png)

 - Không có các hàng xóm khác phía sau router 4, 5, 6 hoặc 7. Họ sẽ gửi trả lời cho router 2 và 3 để cho họ biết họ không biết câu trả lời. Router 2 và 3 sẽ gửi trả lời cho router 1 để nói với nó rằng họ rất tiếc, nhưng đây là câu trả lời , chúng tôi không có tuyến đường nào khác. chúng ta đã dùng rất nhiều gói tin cho việc tìm ra chỉ một tuyến đường mà đã bị mất đúng không?

 ![](https://i.imgur.com/HbRvCFE.png)

 - Hãy làm cho mọi thứ thú vị hơn. Nhìn vào bức ảnh của tôi ở trên và bạn sẽ thấy rằng reply từ router 2 không bao giờ trở lại router 1. EIGRP là một giao thức đáng tin cậy và cho mỗi truy vấn mà router gửi cho các neighbor nó **phải nhận được trả lời trong vòng 3 phút**. Nếu router không nhận được câu trả lời cho TẤT CẢ các truy vấn nổi bật của nó, nó sẽ đặt tuyến đường trong trạng thái SIA (Stuck in Active) và sẽ kill hàng xóm láng giềng. Bằng cách giảm adjacency láng giềng bạn sẽ mất tất cả các tuyến đường bạn đã học được từ hàng xóm này, có nghĩa là bộ định tuyến sẽ bắt đầu gửi truy vấn cho tất cả các tuyến đường khác. đây Không phải là một điều tốt đẹp gì.

 - làm thế nào mà việc trả lời lại không thể trở lại :
 <ul>
 <li>router nhận được truy vấn quá bận vì sự cố bộ nhớ hoặc CPU quá bận. Nó có thể không có cơ hội để xử lý các truy vấn đến hoặc gửi một gói tin trả lời.</li>
 <li>Có vấn đề với liên kết giữa các hàng xóm nên không phải tất cả các gói đều đến nơi</li>
 <li>Bạn có một lỗi liên kết đơn hướng vì vậy các gói tin chỉ đi theo một hướng. Điều này có thể xảy ra với các liên kết fiber.</li>
 </ul>

 - Kể từ IOS 12.1, Cisco quyết định thay đổi quá trình hoạt động để giảm số lượng hàng xóm láng giềng không mong muốn. Họ đã giới thiệu hai gói tin mới gọi là  **SIA query** và ** SIA reply**

 ![](https://i.imgur.com/amFGd84.png)

 - Trước khi Cisco đưa ra SIA query và SIA reply, những điều này sẽ xảy ra:
 <ul>
 <li>1. Router 1 mất thông tin về mạng và không có Feasible successor</li>
 <li>2. Router 1 gửi một truy vấn đến router 2.</li>
 <li>3. Router 2 không biết câu trả lời nên gửi một truy vấn tới router 3.</li>
 <li>4. Router 3 không biết câu trả lời và gửi trả cho router 2.</li>
 <li>5. Router 2 gửi trả lời cho router 1 để cho anh ta biết anh ta không có đầu mối về mạng này</li>
 <li>6. Do tắc nghẽn thư trả lời từ router 2 không bao giờ quay trở lại router 1.</li>
 <li>7. Sau 3 phút router 1 sẽ hủy neighbor adjacency với router 2 bao gồm tất cả các tuyến đường mà nó học được từ router 2.</li>
 </ul>

 - Bây giờ chúng tôi đã có SIA query và SIA Reply và mọi thứ sẽ hoạt động một khác một chút:
 <ul>
 <li>1. router 1 mất thông tin về một mạng và nó không có đường dự phòng feasible successor</li>
 <li>2. router 1 gửi gói query cho router 2</li>
 <li>3. router 2 không biết gì về mạng này nên sẽ gửi gói tin query đến tiếp cho router 3</li>
 <li>4. router 3 không có thông tin về mạng này nên nó gửi trả gói tin reply về cho router 2</li>
 <li>5. Router 2 gửi trả lời cho router 1 để cho anh ta biết anh ta không có đầu mối về mạng này</li>
 <li>6. Bởi vì tắc nghẽn thư trả lời từ router 2 không bao giờ trở lại router 1<l/li>
 <li>7. Sau khi 1,5 phút router 1 sẽ gửi một truy vấn SIA tới router 2 để yêu cầu trạng thái của nó</li>
 <li>8. Router 2 sẽ trả lời bằng một SIA reply và neighbor adjacency sẽ không bị hủy.</li>
 </ul>

 - Điều này có ý nghĩa gì với bạn hay không? Có điều gì khác mà chúng ta có thể làm để ngăn chặn các gói truy vấn được gửi đến ... .EIGRP stub dùng để giải quyết vấn đề này!

 ![](https://i.imgur.com/zetJnwX.png)

 - Xem các topo sau. Chúng tôi có một công ty với trụ sở chính và 2 văn phòng chi nhánh. 2 router HQ được kết nối trên mạng LAN bằng cách sử dụng một link Gigabit. Các văn phòng chi nhánh được kết nối với cả hai router HQ sử dụng đường seial 64kbps chậm. Bạn nghĩ điều gì sẽ xảy ra khi HQ 1 mất tuyến đường đến mạng 1.1.1.0 / 24 ở phía bên trái?

 ![](https://i.imgur.com/jWSN0YV.png)

 - Các gói tin truy vấn (mũi tên màu đỏ) sẽ bay khắp mọi nơi! Nó không phải là một ý tưởng tốt để sử dụng các đường seial để sao lưu vì vậy chúng ta sẽ thay đổi hành vi này bằng cách chuyển các Router branche trở thành các stub EIGRP.

 ![](https://i.imgur.com/7oL5Hna.png)

 - Nếu chúng ta cấu hình các router chi nhánh như các bộ định tuyến gốc họ sẽ **không nhận được truy vấn** từ router HQ của chúng ta. Đây là một kỹ thuật rất tốt để ngăn chặn lưu lượng truy vấn !

 - Tại sao chúng ta gọi nó là một stub? Có lẽ bạn đã từng thấy nó trước đây!
 - Một cây bị cắt đứt được gọi là cây stub ... không có gì dính mắc nữa.
 - Nếu bạn nhìn vào các router chi nhánh chúng giống như một cái cây. Không có router nào khác đằng sau các router chi nhánh và chúng tôi không muốn sử dụng chúng làm đường dẫn sao lưu, vậy tại sao lại hỏi họ về thông tin đường bị mất?
 - 
