# termux_androi_vietnamese
cài đặt:
có thể cài đặt trên google play store (nếu có) hoặc có thể cài đặt trên file afk từ các trang web 
bạn có thể tham khảo file từ một người dùng đã chia sẻ==> https://github.com/termux/termux-app/releases

Mở Termux: Sau khi cài đặt xong, mở ứng dụng Termux.

Cập nhật gói thông tin: Trước khi cài đặt C++, bạn nên cập nhật thông tin về gói (package) bằng cách chạy lệnh sau:

sql
Copy code
pkg update
Cài đặt g++ (GNU C++ Compiler): Bạn có thể cài đặt g++ bằng lệnh sau:

Copy code
pkg install g++
Lệnh này sẽ tải và cài đặt trình biên dịch C++ GNU trên thiết bị của bạn.

Kiểm tra phiên bản C++: Sau khi cài đặt xong, bạn có thể kiểm tra phiên bản của g++ bằng lệnh:

css
Copy code
g++ --version
Lệnh này sẽ hiển thị phiên bản của trình biên dịch C++ đã cài đặt.

Viết và biên dịch chương trình C++: Bây giờ bạn đã có thể viết và biên dịch các chương trình C++ trên Termux. Sử dụng trình soạn thảo như nano hoặc vim để viết mã nguồn, sau đó sử dụng g++ để biên dịch chúng.

Ví dụ:

cpp
Copy code
#include <iostream>

int main() {
    std::cout << "Hello, world!" << std::endl;
    return 0;
}
Để biên dịch chương trình này (ví dụ, lưu trữ trong tệp hello.cpp), bạn có thể sử dụng lệnh sau:

Copy code
g++ -o hello hello.cpp
Sau đó, để chạy chương trình:

bash
Copy code
./hello
Chương trình sẽ in ra dòng "Hello, world!".

Nhớ rằng, để viết code và biên dịch trên Termux, bạn cần có kiến thức về viết mã C++ và sử dụng các trình soạn thảo trong Terminal.
# termux_androi_English
Installation:
You can install it from the Google Play Store (if available) or download the APK file from websites. You can refer to a shared file from a user here: https://github.com/termux/termux-app/releases

Open Termux: After installing, open the Termux app.

Update Package Information: Before installing C++, you should update your package information by running the following command:

sql
Copy code
pkg update
Install g++ (GNU C++ Compiler): You can install g++ with the following command:

cpp
Copy code
pkg install g++
This command will download and install the GNU C++ Compiler on your device.

Check the C++ Version: After installation, you can check the version of g++ using:

css
Copy code
g++ --version
This command will display the installed version of the C++ compiler.

Write and Compile a C++ Program: Now, you can write and compile C++ programs on Termux. Use editors like nano or vim to write your code, then use g++ to compile them.

Example:

cpp
Copy code
#include <iostream>

int main() {
    std::cout << "Hello, world!" << std::endl;
    return 0;
}
To compile this program (for example, if saved in a file named hello.cpp), you can use:

bash
Copy code
g++ -o hello hello.cpp
Then, to run the program:

bash
Copy code
./hello
The program will print "Hello, world!".

Remember, to code and compile on Termux, you should have knowledge about C++ programming and how to use terminal-based editors.




