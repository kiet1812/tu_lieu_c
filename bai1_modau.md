# **Mở đầu**
## **Cấu trúc C++ cơ bản**
```c++
#include <bits/stdc++.h> // thư viện chuyên cho ae giải toán tin
using namespace std; // tự lên gg tìm hiểu nha 
// khai báo hàm main chính

int main(){
	cout<<"Hello world"; // in ra màn hình dòng chữ hello world
	return 0; // trả về giá trị cho hàm
}
```

## **Kiến thức cơ bản**

### **1. Khai báo biến**

Trong C++ có những kiểu dữ liệu sau

- ***Integers(số nguyên)***
```c++
int a;   //dòng này có nghĩa là khai báo biến a là kiểu dữ liệu int(số nguyên)
long long b; // dòng này thì cũng khai báo biến b là số nguyên
```
Tuy nhiên kiểu long long chứa đc giá trị
10^9
còn int chỉ chứa được
10^6
(hình như thế k rõ số liệu lắm ^.^)

Nhưng kiểu long long tốn `8 byte` để mã hóa còn int chỉ tốn `4 byte` nên việc lạm dụng long long sẽ làm tăng thời gian chạy chương trình

- ***Số thực***
```c++
float x; // khai báo biến x là kiểu dữ liệu float(số thực)
double y; // khai báo biến x là kiểu số thực
```
Cũng giống int và long long, float và double cx tương tự như trên thôi nha
- ***Bool(Đúng sai)***
Kiểu này đặc biệt hơn, nó chỉ trả về giá trị 1(true) hoặc 0(false)
```c++
bool z; //khai báo kiểu dữ liệu z là kiểu dữ liệu bool
```
- ***Char(kí tự)***
Kiểu này dùng để khai báo các ký tự từ a->z và từ A->Z
```c++
char c; //khai báo biến c là kiểu dữ liệu char
```
**Lưu ý:** _mỗi biến có kiểu dữ liệu char chỉ chứa đc 1 ký tự chứ không thể chứa được một chuỗi kí tự_

***Còn vài kiểu dữ liệu đặc biệt thì sau sẽ học nhé***

### **2. Nhập xuất**

- **Nhập(input)**
Là lấy dữ liệu từ bên ngoài chương trình vidu như từ bàn phím hoặc từ 1 file nào đó
```c++
cin>>a; //vidu biến a là kiểu int thì cin>>a có nghĩa gán cho a 1 giá trị từ bên ngoài
```
**Lưu ý:** _nếu khai báo biến int nhưng nhập vào kiểu số thực thì máy sẽ tự chuyển nó thành số nguyên_

vidu khai báo biến a là int nhưng nhập vào số 5.3 thì lúc xuất ra biến a sẽ là 5 thôi

- **Xuất(output)**
In(hiển thị) ra màn hình hoặc ra một file nào đó
```c++
cout<<a;//xuất ra giá trị của biến a vidu bên trên là cin>>a; và nếu đầu vào là 10 thì nó sẽ in ra màn hình là số 10
```

***Hết rồi bye bye :v***
