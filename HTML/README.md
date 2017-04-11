# HTML

##I.HTML là gì? Vai trò của HTML?

- `HTML` viết tắt của *hyper text markup language.

- Luôn được đặt trong dấu `<>` và kết thúc `</>`

<li> Vd: <>nội dung</>   </li>

-***note***: lưu với đuôi`.html`

- 1 đoạn `html` phãi có thẻ mở, thẻ đống.

--> nhưng có một sô thẻ không có thẻ đống

- Khai báo văn bản: 

<ul>
<li> Thuộc tính bằng chữ, có dấu bằng đằng sau thuộc tính.</li>
<li> Mỗi thuộc tính cách nhau một khoảng trắng.</li>
</ul>

##II.Cấu trúc của một HTML:

```

<!DOCTYPE html>

<html>

  <head>
  
    <title>Tiêu đề</title>
    
  </head>

  <body>

    <h1>tiêu đề lớn nhất</h1>
    
    <p>đoạn văn bản.</p>

  </body>
  
</html>

```

##III. Soạn thảo HTML đầu tiền:

- ***Tiêu đề<heading>***: gồm có 6 tiêu đề

```<ul>

 `<h1>noidung</h1>` Đây là tiêu đề lớn nhất
 
 `<h2>noidung</h2>` Đây là tiêu đề lớn thứ 2 
 
 ....................
 
 `<h6>noidung</h6>` Đây là tiêu đề nhỏ nhất.
 
</ul>

```
 
 -***Đoạn văn trong HTML***: (paragraph)
 
``` 

 <p> nội dung </p> 
 
```
 
 -***Link trong HTML:***
 
<li>` <a href="đường link">click link</a> </li>`


-***Chèn ảnh trong HTML:***

<li> `<img src="ảnh.jpg" alt="W3Schools.com" width="104" height="142">` </li>

-**Khai báo ngôn ngữ:***

<li> `<html lang="vi"></html> ` --- </li>

<li> **vi** là ngôn ngữ tiếng việt </li>

<li>**"en-us"** --- ngôn ngữ tiếng anh </li>

##IV:Thẻ Khai báo Thông tin website:

<li> ***Phãi đặt trong thẻ*** `<head>...</head>`</li>

- <i> Thẻ tiêu đề:<./i> `<title> tên tiêu đề </title>`

- <i> Thẻ:</i> `<meta charset="utf-8"/>`

- <i> Thẻ:</i> `<meta name="description" content= "Học HTML cơ bản tại https://www.w3schools.com:"/>`

- <i> Thẻ:</i> `<meta name="author" content="w3schook.com"/>`

- <i> Thẻ:</i> `<meta name="keyword" content="Hoc HTML"/>`

<li>***content: khai báo thuộc tính dữ liệu cửa thẻ***</li>

##V.Các Thẻ định dạng văn bản:

      **Phải đặt trong :** `<body> .... </body>`
      
- <i>Thẻ tiêu đề: </i> 

```
<h1> ...</h1> ==> To nhất

<h2> ...</h2>

...

<h6>...</h6> ==> nhỏ nhất

```
- <i> Khai báo đoạn văn bản: </i>

```
<p> Đoạn văn bản 1 </p>

<p> Đoạn văn bản 2 </p>

```
- <i> in đậm, in nghiêng, gạch chân và kẻ ngang: </i>

``` 
In đậm:       <strong> .... </strong>

In đậm trog 1 đoạn văn:<p>Le thi <b> Dieu Thuy </b> </p>

In nghiêng :  <i>....</i>

In nghiêng trong 1 đoạn văn: <p>Le Thi <em>DieuThuy</em></p>

Gạch chân:    <u>...</u>

Kẻ ngang:     <strike>...</strike>

Chữ nhỏ trong tiêu đề : <h2>HTML <small>Small</small> Formatting</h2>

Tô chữ: <h2>HTML <mark>Marked</mark> Formatting</h2>

Xóa từ :<p>My favorite color is <del>blue</del> red.</p>

```

-<i> Tạo dòng kẻ ngang cho đẹp mắt: </i>

`<hr>`

-<i> Dấu ngoặc kép: `<q>..</q>`

-<li> Căn lề : <blockquote></...>

-<i> Thẻ xuống dòng</i>
`<br>`
-VD: <p>Le thi <br> Dieu thuy </p>

-<i> Thẻ trích dẫn:</i>

```
<quote>"Dieuthuy"

  <cite>
  
  Làm nổi bật trong trích dẫn
  
  </cite>
  
  </quote>
  
 ```
 
 -<i> Thẻ định dạng sẳn: </i>
 
```
<pre>

  Đoạn văn bản 1
  Đoạn văn bản 2
  Đoạn văn bản 3
  
 </pre>
 
 ```
-<i>Tiêu đề trong đoạn văn:</i>

`<p title="Học HTML">Hoc ngôn ngữ html.</p> ` 


 -<i>Thẻ code:</i>
 
 `<p>Biến<code>$w3school['website']</code></p>`
 
 -<i> Định dạng chữ : </i>
 
 `<p style="..."> Đây là văn bản thuộc tính <code>style</code> `
 
 -Trong "..." có: 
 
 <ul>
 
 <li> text-alige: Căn lề văn bản</li>
 
  <ul>
  
  <li> left: căn lề trái.</li>
  
  <li> right: Căn lề phải.</li>
  
  <li> center: Căn giữa.</li>
  
  </ul>
  
  <li>font family (font chữ) </li>
  
  <li>color: (trong bảng màu sắc).</li>
  
  <li>backgroud- color(màu nền).</li>
  
  <li>font size. </li>
  
  </ul>
  
  -<strong>Note</strong>: các thuộc tính cách nhau bởi dấu **phẩy**.
  
  - Lệnh: `<span style="">...</span>` dùng để làm màu một, hoặc nhiều chữ trong một đoạn văn .
  
  -<li> Ghi chú thích: `<!--..........-->` </li>
 
   
##VI:Thẻ tạo danh sách trong HTML:

-***Loại danh sách có sắp xếp:*** hiển thị theo thứ tự, được đánh dấu 1,2,3.... hay a,b,c,....

<li>Ví dụ:</li>

``` <h3> Danh sách xắp xếp: </h3>

    <ol>
    
    <li> Mục con 1</li>
    
    <li> Mục con 2</li>
    
    <li> Mục con 3</li>
    
    </ol>
    
 ```
 
 <li> *Note:* Nếu muốn sắp xếp khác:</li>
 
 ```
 
 <h3> Danh sách sắp xếp </h3>
 
 <ol type="I">---> <i>sắp xếp theo chữ số la mã</i>
 
 <li>Mục con 1</li>
 
 <li>Mục con 2</li>
 
 </ol>
 
 ```
 
 <li>***Note:***</li>
 
 <ul>
 
 <li>nếu type="1" thì sắp xếp theo số thứ tự 1,2,3....</li>
 
 <li> nếu type="a" thì sắp xếp theo a,b,c,d.....</li>
 
 <li> Nếu type="A" thì sắp xếp theo A,B,C,D .... </li>
 
 </ul>
 
 - ***Loại danh sạch không sắp xếp:***
 
 ```
 <h3>Danh sách không sắp xếp</h3>
 
 <ul>
 
 <li> Mục con 1</li>
 
 <li> mục con 2</li>
 
 </ul>
 
 ```
 
 -***Danh mục có mô tả:***
 
 ```
 
 <h3>Danh sách có mô tả</h3>
 
 <dl>
 
      <dt> Word press </dt>
      
      <dd> Mã nguồn tọa blog </dd>
      
      <dt> HTML</dt>
      
      <dd> Là ngôn ngữ đánh dấu văn bản</dd>
      
      <dt> CSS </dt>
      
      <dd> Ngôn ngữ thêm style cho HTML</dd>
      
 </dl>
 
 ```
 
 ##VII: Tạo liên kết và chèn hình ảnh, chèn website:
 
 ###1: Thẻ chèn liên kết: 
 
 - `<a href="https://www.w3schools.com">This is a link</a>`
 
 - `<li><a href="text.html" title="xem nội dung text.html" targer="_brank;_self"> HTML</a></li>`
 
 <ul>Trong đó: 
 
 <li>target: Thiết lập cửa sổ mở tập tin.</li>
 
 <li> _brank: Thiết lập mở tập tin cho cửa sổ mới. </li>
 
 <li> _self: mở tập tin trên cửa sổ hiện tại . </li>
 
 <li> ***Note:***</li>
 
 ```
 <h3><a href="#noidung">Xem nội dung</a></h3>
 
 <h4 id="noidung"> Nội dung chính</h4>
 
 ```
 
 ***Khi nhấp vào nội dung ở h3 thì sẽ lập tức di chuyển tới h4.***
 
 ###2: Thẻ chèn hình ảnh: 
 
 -`<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">`
 
 -`<img src="w3schools.jpg" alt="W3school.com" titler="Xem ảnh" width="152px" height="550px">
 
 ###3. Chèn website:
 
 `<iframe src="demo_iframe.htm" height="200" width="300"></iframe>`
 
##VIII: Tạo bảng:

###1.Bảng không có khung: 

```
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
   </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td> 
    <td>94</td> 
  </tr>
  <tr>
    <td>John</td> 
    <td>Doe</td>
    <td>80</td>    
  </tr>
</table>
```

###2. Bảng có khung: 

```
 <!DOCTYPE html> 
<html>
<head>
<style>
  table, th, td { 
    border: 1px solid black;    
  (hoặc:  border-collapse: collapse;)}                 
</style>
</head>
<body>
<table style="width:100%">
  <tr> 
    <th>Firstname</th>    
    <th>Lastname</th>     
    <th>Age</th>    
  </tr>  
  <tr>  
    <td>Jill</td>   
    <td>Smith</td>    
    <td>50</td>    
  </tr>  
  <tr>
    <td>Eve</td>    
    <td>Jackson</td>    
    <td>94</td>    
  </tr>  
  <tr> 
    <td>John</td>    
    <td>Doe</td>    
    <td>80</td>   
  </tr>  
</table>
</body>
</html>
```

##IX:FORM:

###1.Đăng nhập : 
<p><code>
```
<form action="đăng nhập">

  username:<br>
  
  <input type="text" name="username" >
  
  </br>
  
  password:<br>
  
  <input type="text" name="password">
  
  <br><br>
  
  <input type="submit" value="gửi đi"name="submit"></br>
  
</form> 
```
</code></p>
 



         



 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 








