# LazyToolBox 1.0
Photoshop Extension<br />
my FB page: https://www.facebook.com/lethanhtung0209
----------------------------------------------------------------------------------------------------
Many thanks to SLEIPNIR for his original idea and lasso scripts!<br />
https://github.com/roguesleipnir

i have update and modified SLEIPNIR's script with an user interface with a HTML5 panel with on/off button and add some other functions to fasten up my workflow.
the script is pretty simple but useful, the interface talk with adobe extend script through Adobe Common Extensibility Platform.

----------------------------------------------------------------------------------------------------

[TIẾNG VIỆT]

![alt text](https://github.com/m-myopia/LazyToolBox/blob/master/README_IMG/interface.jpg)

Hướng dẫn download cho ai không rành github thì nút download ở chỗ này :D
![alt text](https://github.com/m-myopia/LazyToolBox/blob/master/README_IMG/download.jpg)


*note: Có thể giữ shift khi dùng lasso để xóa trong vùng chọn
*Có thể sử dụng với bất kỳ tool nào khi ở chế độ khoanh vùng



[Hướng dẫn cài]

1.chép 2 file "LassoFill_Main.jsx" và "LassoFill_AddListener.jsx" vào  C:\Program Files\Adobe\Adobe Photoshop CC 2019(còn tùy vào phiên bản bạn đang sử dụng)\Presets\Scripts

2.chép folder "com.myopia.lazytoolbox" vào 
[với window 64 bit]
"C:\Program Files (x86)\Common Files\Adobe\CEP\extensions"
[với window 32 bit]
"C:\Program Files\Common Files\Adobe\CEP\extensions"

3.khởi động photoshop, vào file --> Scripts chạy file "LassoFill_AddListener" một lần đầu tiên để cài scripts trigger.

4.chạy extension từ Window --> Extensions --> LazyToolBox

-------------------------------------------------------

5.LƯU Ý: nếu có vấn đề không sử dụng được có thể mở file "LassoFill_Main.jsx" bằng notepad hoặc phần mềm chỉnh sửa văn bản bất kỳ edit dòng sau:

SettingFile = File("/Program Files (x86)/Common Files/Adobe/CEP/extensions/com.myopia.lazytoolbox/host/MyopiaSettings.txt");

--------------------------------------------------------
/Program Files (x86)/Common Files/Adobe/CEP/extensions
-------------------------------------------------------
thay thế phần trên bằng đường dẫn nơi đã copy thư mục "com.myopia.lazytoolbox"

ví dụ:  \Program Files\Common Files\Adobe\CEP\extensions
đối với window 32 bit, sau đó copy trả lại folder "com.myopia.lazytoolbox" theo bước một



Have Fun


