# Hướng dẫn thêm bài vào hệ thống

* Bài viết này có bản video

## Video hướng dẫn
- Bài biết sẽ chứa thông tin bổ trợ cho video, ae nên xem video này trước khi đọc bài viết.

- [Video hướng dẫn thêm bài vào hệ thống](https://drive.google.com/file/d/10CEPy8ozyASMWJzyYNVSC9j_gb6i7JaY/view?usp=sharing)

  

## Xin quyền

- Liên hệ admin để xin quyền thêm bài.
  1. Sơn Đinh
      Email: sondc99@gmail.com
      Facebook: https://www.facebook.com/sonanhnb/
  2. Hải Trịnh
  Email: trinhxhai@gmail.com
  Facebook: https://www.facebook.com/profile.php?id=100010755634310
  3. Thắng Phan
  Email: pdthang2000@gmail.com
  Facebook: https://www.facebook.com/thang.phan.184881
  4. Tuấn Anh
  Email: letuananh14122000@gmail.com
  Facebook: https://www.facebook.com/tuanssanhss.le

## Hướng dẫn.

- Truy cập http://olp.hou.edu.vn/, đăng nhập.
- Tại góc trên bên phải, di chuột vào tài khoản, chọn **Quản trị**.

![image](https://drive.google.com/uc?export=view&id=1uqRCVa9KF4sfzYZxpR1XSWJ8I70n3CrO)

- Tại thanh điều hướng bên trái chọn đề bài, tại màn hình chính chọn, thêm vào.

![image](https://drive.google.com/uc?export=view&id=1r8U0ucbXAwpIpb1y_7wojclmqLmP8v3K)



- Mình sẽ chú thích thêm về các trường này

  - Công khai.
    - Thường các bài tập chia làm 2 mục đích, luyện tập và contest sắp tới, nếu là cho contest sắp tới thì ae không cần tích trường này. 
    - Các bài trong contest đến giờ sẽ tự động public để các thí sinh tham gia có thể đọc đề, tuy nhiên sau khi hết contest ae sẽ phải vào tích lại trường này để các thí sinh có thể nộp lại bài này.
  - Bài toán (Đề bài).
    - Mình sẽ hướng dẫn cách viết đề bài sao cho dễ nhìn hơn ở mục dưới.
  - Kiểu vấn đề (Problems Types)
    - Là mục nhỏ hơn của **Nhóm đề bài (Problems Groups)**.
    - Vd : Chặt nhị phân với số thực, Chặt nhị phân với tổng tiền tố, ICPC Graphs Problems.
  - Nhóm của đề bài (Problems Groups)
    - Khi trang web khi tìm kiếm problemssẽ có select box lọc theo trường này, ae chú ý đặt sao cho có hệ thống, vd ae muốn tìm các problems cho beginner thì chỉ cần 1 lân.
    - Vd : Luyện tập ICPC, Luyện Tập OLP, Graphs, DP , Chặt nhị phân.
  - Giới hạn bộ nhớ :
    - Thường nếu vấn đề của ae không liên quan đến bộ nhớ, hay không yêu cầu vệ bộ nhớ thì có thể để là 524288 (tương đương với 512 mb).
  - Ngôn ngữ cho phép:
    - Tích hết các ô C/C++
    - Sau các bạn có phát triển được thêm thì có thể sửa text này.

  



## Hướng dẫn viết đề bài.

Hệ thống sử dụng Markdown hỗ trợ cho việc viết đề bài, về cú pháp các bạn có thể tham khảo link sau.

- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

#### Phần mềm hỗ trợ:

- Mình dùng [Typora](https://typora.io/), toggle (Ctr + /) khá tiện, các bạn có thể thử, tuy nhiên các biểu thức latext phải để trong dấu $$ thay vì ~~ trên hệ thống, mình lười chưa tìm được cách tối ưu hơn, ae có thể tìm.


#### Biểu thức toán học

Để biểu diễn các biểu thức toán học các bạn có thể tham khảo link sau, các cú pháp tham khảo trong link dưới các bạn cần phải để vào giữa hai đấu "~" để có thể render ra đúng vd mình tìm trong link kia được mẫu cho biểu thức tổng như sau.
![image](https://drive.google.com/uc?export=view&id=1zmtAO2EU10zXeoEy6fw-JQ12o_133UUY)
Mình có thể viết là.

``` markdown
~ \sum_{k=1}^N k^2 ~
```



> https://en.wikipedia.org/wiki/Help:Displaying_a_formula



#### Hình ảnh minh họa

- Để quản lí gọn hình ảnh, tất cả các ảnh trong bài viết sé được lưu chung trong cùng 1 tài khoản google drive được quản lí, hãy liên hệ với người quản lí clb để xin thư mục.

- Thêm ảnh vào thư mục nhận được, chuột phải ảnh, chọn **Chia sẻ **.

- Ở phần Nhận đường liên kết, thay đổi đối tượng thành **Bất kì ai có đường liên kết**, và quyền là **Người xem**.

- Sao chép đường liên kết tới ảnh, liên kết sẽ có dạng sau https://drive.google.com/file/d/<FILE_ID>/view , ta đổi thành https://drive.google.com/uc?export=view&id=/**<FILE_ID>** và dùng link này làm link của ảnh.

- Trong document ta thêm text sau :  

``` markdown
	![image](https://drive.google.com/uc?export=view&id=<FILE_ID>)
```



> https://stackoverflow.com/questions/52063556/add-image-to-github-readme-md-from-google-drive



## Sinh test
#### Sinh test

- Có nhiều cách để sinh test, đây là cách của mình, flow như sau.
- Flow sinh test này có thể có nhiều chỗ cần cải thiện, nếu ae có cách tiện hơn hãy nhắn với mình.


##### 1. Giải bài và sinh input
- Giải bài dùng cin cout như bình thường **(sol.cpp)**
- Test có thể viết bằng tay hoặc random, dùng for để random các test liên tục, định dạng xx.in **(gt.cpp)**

##### 2. Dùng solution (sol.cpp) để giải test đưa ra output(xx.out) tương ứng
- **Sau khi compile** sol.cpp (g++ sol.cpp -o sol), sử dụng command sau để nhận input vào từ xx.in và xuất kết quả ra file xx.out (ga.cpp), tương ứng.

``` command line
sol < test/xx.in > test/xx.out	
```

- **test** là một thư mục, để ta có thể dễ dàng zip.
- Để không phải gõ lệnh này nhiều ta sử dụng lệnh **system(cmd);** được hỗ trợ trong c++ kết hợp với vòng lặp , để chạy các lệnh trên cmd để sinh file kết quả (xx.out) .
- Sau đó ta nép thư mục test (bao gồm các file.in và file.out)

##### code
- Đây là ví dụ về code sinh test của bài Hello World, đề là nhận vào 1 xâu s, in ra "Hello, " + s.
###### sol.cpp

```cpp
#include <bits/stdc++.h>
using namespace std;
int main() {
	string s;
	cin >> s;
	cout << "Hello, " + s << endl;
}
```
###### gt.cpp

```cpp
#include <bits/stdc++.h>
using namespace std;

// chỉ sử dụng khi số lượng test <= 99 - 2 chữ số
string namingTest(string test) {
    while (test.length() < 2) test = "0" + test;
    return test;
}

int main()
{

    string inpName ;
    srand(time(NULL));
    int tFrom = 2;
    int tTo = 10;

    vector<char> src;
    for (char i = 'a' ; i <= 'z' ; i++ ) {
        src.epb(i);
    }
    for (char i = 'A' ; i <= 'Z' ; i++ ) {
        src.epb(i);
    }


    for (int iTest = tFrom; iTest <= tTo; iTest++)
    {

        string sfi = namingTest(to_string(iTest));
        // create file input
        ofstream fo("test/" + sfi + ".in");

        // begin write test
        // fo << meh

        string s;
        const int maxLen = 100;

        for (int i = 0 ; i < maxLen ; i++) {
            s += src[ rand()%sz(src) ];
        }

        fo<<s<<endl;

        // end write test

        cout << " Done write test " + to_string(iTest) + " !" << endl;
        fo.close();
    }

    return 0;
}

```
###### ga.cpp

```cpp
#include <bits/stdc++.h>
using namespace std;

#define len(s) (int)s.length()

void namingTest(string &test){
    while(test.length()<2) test= "0"+test;
}

int main(){
    string name;
    int fromT = 1;
    int toT = 10;
    for(int itest = fromT ; itest <= toT ; itest++){

        name = to_string(itest);
        namingTest(name);

        // begin : run ur code
        string scmd = "sol < test/" + name + ".in > test/"+ name + ".out";
        cout<<scmd<<endl;
        char cmd[ len(scmd) + 1 ];
        strcpy(cmd,scmd.c_str());

        //show(cmd);
        system(cmd);
        // end  : your code
        
        cout<<"Done write ans "<<itest<<" !"<<endl;
    }

}
```


#### Thêm test vào bài


Sau khi thêm bài thành công, nhấp vào tên đề bài để xem bài, bên trên góc phải các bạn chọn xem trên web. Hoặc vào lại problems đó bằng trang quản trị.

![image](https://drive.google.com/uc?export=view&id=1ZzqMydGl0_lxXEosdl2bXftZ1oJ_bqPA)

Tiếp đó góc phải chọn **sửa đổi test** .

![image](https://drive.google.com/uc?export=view&id=1im4LsrdXtp553TGvwSvQu3_eVFPpMHl9)






![image](https://drive.google.com/uc?export=view&id=1pdHONpllaYr6pTTgQK0H9gaEFE8ios-p)



- Ae chọn file nén test của mình, đuôi .zip . **(1)**
- Nhấn **Nộp bài**.
- Đoạn này ae có thể nhận được 1 dòng thống báo đỏ "Điểm phải được xác định cho các trường hợp không theo lô #1.", ae có thể kệ dòng nay, nếu nội dung khác thì ae phải xem lại test của mình. Thấy test có hiển lên ở phần **(1)** là được..
- Tiếp đến tùy vào bài của ae là dạng ICPC, hay OLP ae chọn options tương ứng trong select box ở **(2)** , nhấp Fill testcase **(2)**.
- Sau khi test các test case đã được hiện ở dưới, nhấn Nộp bài thêm lần nữa để hoàn thành.

