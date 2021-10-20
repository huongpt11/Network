# Network
base
### CCNA T_T

-----


# 1. [Lap equiqment](#lapequiqment)
*include: 
   + GNS3
   + Cisco catalyst 2950
   + Cisco catalyst3550
   
# 2. [ Basics networking](#)
- Personal computers(PC): nhận và gửi dữ liệu
- interconections:(đảm bảo dữ liệu truyền)
   + Network cards
   + Media 
   + Conector
- Switches(bộ chuyển mạch)
- Router(đinh tuyến): kết nối các mạng và chọn con đường tốt nhất dẫn đến các mạng. 
# 3. [OSI-model](#osimodel)
 > **Chia làm 7 lớp:**
- 7 Application: Cung cấp dịch vụ mạng
- 6 Presentation: Đại diện dữ liệu
- 5 Sesion: Truyền liên Host
- 4 Transport ( đơn vị **segment**): quản lí kết nối đầu cuối
- 3 Network (đơn vị **packets**): phân bố dữ liệu
- 2 Data link (đơn vị **Frames**): liên kết dữ liệu
- 1 Physycal (**bits**): vật lý
# 4. [TCP/IP-Model](#)
 > **Chia làm 4 lớp:**
- Application 
- Transport 
- Internet 
- Network access
# 5. [The transport layer: UDP and TCP](#)
## 5.a **UDP**
- Basic: 
   - hoạt động ở OSI và TCP/IP thuộc Transport layer
   - cho phép truy nhập mạng
   - kiểm tra lỗi giới hạn
   - không phục hồi dữ liệu 
- UDP header:
![!](https://tailamblog.files.wordpress.com/2017/08/58.png?w=371&h=158)

## 5.b **TCP**
- Basic:
    - Kết nối trước
    - Truyền nhận mọi thời điểm
    - Đánh STT
    - Báo nhận
    - Phục hồi dữ liệu
- TCP header:
![!](https://cuongquach.com/resources/images/2017/08/h1.png)
- 3 way handsnake
- flow control
- **SO SÁNH**
![!](https://vnpro.vn/upload/user/images/Th%C6%B0%20Vi%E1%BB%87n/h%C3%ACnh%201.jpg)
# 6. [Ethernet LAN](#)
- LAN componets:
    - Computer: PC, service
    - Interconnections: NICS, Media
    - Network devices: Hub, switches, routers
    - Protocol: Ethernet, IP, ARP, DHCP
- Chức năng:
    - chia sẻ dữ liệu ứng dụng
    - tài nguyên
    - kết nối khác
- Phân loại:
    - Soho LAN
    - Elterprise LAN 
- Cấu trúc:
![!](https://st.quantrimang.com/photos/image/2018/04/18/mang-ethernet-1.png)

- CSMA/CD: giarm thiểu xung đột
- Các loại truyền thông trong một mạng LAN:
    - Unicat
    - Broadcat
    - Multicast
# 7.[IP](#)
- IP header:
![!](https://tailamblog.files.wordpress.com/2017/08/75.png?w=371&h=206)

- Cấu trúc địa chỉ IP:
    - Các bit phần mạng không được đồng thời bằng 0
    - Host=0 là **địa chỉ mạng**
    - Host=1 là **broadcast**
- Các lớp địa chỉ IP:
![!](https://voer.edu.vn/file/31712)
