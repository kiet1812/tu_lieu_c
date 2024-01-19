# Các phép tính trong C++
## **1. Các phép tính cơ bản**
Trong C++ có các phép tính cơ bản như
`+` _cộng_ `-` _trừ_ `*` _nhân_ `/` _chia_
Nếu muốn `cộng` 2 số ta có thể làm như sau

```c++
#include <bits/stdc++.h>
using namespace std;
int main(){
	int a, b;
	a = 5;
	b = 6;
	cout<<a+b;
	return 0;
}
```


**Output** của đoạn code trên sẽ là `11`

_**Tương tự như thế các phép trừ nhân chia cũng như vậy**_
nếu 2 giá trị cần `cộng` là số thực thì vẫn OK nha
## **2.Các phép toán logic**
Với kiểu `bool` ta có các phép logic sau
`<` là dấu bé, `>` là dấu lớn, `<=` hay `=<` là bé hơn hoặc bằng, `>=` hay `=>` là lớn hơn hoặc bằng
ngoài ra ta có phép so sánh bằng kí hiệu là `==` dùng khi cần so sánh 2 số có bằng nhau hay không
ta cũng có phép so sánh khác kí hiệu là `!=` ngược nghĩa với `==`

**Dưới đây là một ví dụ:**
```c++
#include <bits/stdc++.h>
using namespace std;
int main(){
	bool a = 5==6;
	cout<<a;
	return 0;
}
```
**Output** sẽ là `0 (false)` vì **5 không thể bằng 6** nên sẽ trả về giá trị sai, nếu thay dấu `==` thành `!=` thì chương trình sẽ trả về giá trị `1 (đúng)`
_**Tương tự như với các phép toán logic khác cũng được sử dụng như thế**_

Ta có cx các phép logic trong lập trình như `&&` là and, `||` là hoặc và `!` là not
thường được dùng khi có 2 phép logic trở lên 
**Ví dụ:** Viết chương trình nhập vào năm y kiểm tra xem năm y có phải năm nhuận `năm nhuận là năm chia hết cho 400 hoặc 4 nhưng không chia hết cho 100` hay không nếu đúng thì trả về số 1 nếu không thì trả về số 0.
```c++
#include <bits/stdc++.h>
using namespace std;
int main(){
	int y; cin >> y;
	bool x = (y % 400 == 0) || (y % 4 == 0) && (y % 100 != 0);
	cout << x;
	return 0; 
}
```

## The End
