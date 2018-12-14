## Chào mừng Các bạn đến với { HCJ TEAM }

Cách sử dụng padding, margin trong BS4
======================================

## Nội dung chính

* [p|m][location]-[size]

Website Tham khảo ：

https://getbootstrap.com/docs/4.0/utilities/spacing/

### Hướng dẫn cách dùng 

p:padding
m:margin

location:
- t, b, l, r
  - t:top
  - b:bottom
  - l:left
  - r:right
- x, y
  - x:lr
  - y:tb

size:
- 0
- 1:0.25rem
- 2:0.5rem
- 3:1.0rem
- 4:1.5rem
- 5:3.0rem
- auto

#### Rem là cái gì ?

Kích thước phần tử con sẽ dược dựa theo phần tử Cha 

Website Tham chiếu：

https://developer.mozilla.org/zh-CN/docs/Web/CSS/length

## Bài thập thực hành

~~~html
<style>
    .my-container {
        width: 200px;
        height: 200px;
        background: #ddd;
        margin-bottom: 5px;
    }
</style>
...
<div class="my-container pt-3 pl-3">
    <div class="bg-primary w-50 h-50 pt-1 pl-2"> { ThanhDevs } </div>
</div>
<div class="my-container px-3 py-3">
    <div class="bg-success w-100 h-100"> { ThanhDevs } </div>
</div>
~~~

## Video & Codes

* Mỗi một video sẽ chỉ bao gồm 1 nội dung chính và chỉ được khống chế trong 5 -15 phút 
* Nội dung code 
  - Git@
    https://github.com/ThanhDevs/LearnBootstrap4

  - Blog@
    http://lavanthanh.com

## ThanhDevs

* Sau cùng sẽ dùng Bootstrap4 để thực hành dựng một layout blog cá nhân, Hoan nghênh các bạn đăng ký và đón xem video nhé