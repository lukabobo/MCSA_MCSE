## Note lại cách cài đặt dịch vụ WSUS trên Windows server 2019

Mô hình:

!

## Add role RDS

Thực hiện trên máy WSUS server

Trước hết, join RDS server vào domain dungdb.local

Sau đó add role cho WSUS theo các bước dưới đây:

![Imgur](https://i.imgur.com/IPYu5wU.png)

![Imgur](https://i.imgur.com/MhZGGxy.png)

![Imgur](https://i.imgur.com/es23tZ1.png)

![Imgur](https://i.imgur.com/oKfmrxf.png)

![Imgur](https://i.imgur.com/53QeoeM.png)

![Imgur](https://i.imgur.com/3E9dW7O.png)

![Imgur](https://i.imgur.com/T2M503R.png)

![Imgur](https://i.imgur.com/1ojDrSg.png)

![Imgur](https://i.imgur.com/scs5GGX.png)

Điền vào đường dẫn mà chúng ta sẽ đặt các file windows update tại đó. Ví dụ: 

![Imgur](https://i.imgur.com/tMSnerM.png)

![Imgur](https://i.imgur.com/AMBhSZs.png)

![Imgur](https://i.imgur.com/gQ9Swrw.png)

![Imgur](https://i.imgur.com/p0MVzP4.png)

Chờ quá trình cài đặt diễn ra

![Imgur](https://i.imgur.com/LfPfLm9.png)

![Imgur](https://i.imgur.com/oEnx41D.png)

## Cấu hình

![Imgur](https://i.imgur.com/E81kuFz.png)

![Imgur](https://i.imgur.com/HKGBQcK.png)

![Imgur](https://i.imgur.com/zFvv9lp.png)

![Imgur](https://i.imgur.com/o3qL9oF.png)

![Imgur](https://i.imgur.com/0moxRzb.png)

![Imgur](https://i.imgur.com/jfE92g0.png)

Quá trình này sẽ hơi lâu, và có phụ thuộc vào tốc độ đường truyền của bạn.

![Imgur](https://i.imgur.com/UZT3B0k.png)

![Imgur](https://i.imgur.com/f2Z0DeS.png)

![Imgur](https://i.imgur.com/1gu4YTu.png)

![Imgur](https://i.imgur.com/4DP29DO.png)

Chọn thời điểm update tùy nhu cầu sử dụng. Ở đây tôi chọn update thủ công.

![Imgur](https://i.imgur.com/gwFftbU.png)

![Imgur](https://i.imgur.com/rqCfVEI.png)

![Imgur](https://i.imgur.com/MdED0J6.png)

Như vậy là đã cấu hình xong

Sau khi chờ đồng bộ, chúng ta có thể thấy có bao nhiêu bản cập nhật ở đây.

