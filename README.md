# jquery.ThaiAddress.En-Th.js
ระบบออโต้คอมพลีตที่อยู่ ตำบล อำเภอ จังหวัด รหัสไปรษณีย์ ทั้งภาษาไทยและภาษาอังกฤษ

ระบบนี้ได้แนวคิดมาจาก https://github.com/earthchie/jquery.Thailand.js/ โดยเขียนขึ้นมาใหม่ทั้งหมดและเพิ่มส่วนของภาษาอังกฤษขึ้นมา ตัวไลบรารีจะไม่ได้เรียกใช้โค้ดอื่นใดนอกจาก jQuery ทำให้สะดวกเวลาใช้งาน ข้อมูลชื่อตำบล อำเภอ จังหวัด ในส่วนของภาษาอังกฤษได้จากคุณ https://github.com/leekung ขอบคุณทุกท่านไว้ ณ ทีนี้

หากต้องการแก้ไขไม่ว่าส่วนใดก็ตาม เชิญ Fork และแก้ไขตามสะดวก

## ตัวอย่าง
https://lookhin.github.io/jquery.ThaiAddress.En-Th.js/index.html?rand=123

![ตัวอย่าง](https://lookhin.github.io/jquery.ThaiAddress.En-Th.js/images/example.jpg "ตัวอย่าง")

## ตัวอย่างโค้ด

```JavaScript
$(function () {
    // ฟอร์มภาษาไทย
    $.ThaiAddressEnTh({
        lang: 'TH',
        database: 'js/thai_address_database_en_th.js',
        district: $('#district_th'),
        amphoe: $('#amphoe_th'),
        province: $('#province_th'),
        zipcode: $('#zipcode_th')
    });

    // ฟอร์มภาษาอังกฤษ
    $.ThaiAddressEnTh({
        lang: 'EN',
        database: 'js/thai_address_database_en_th.js',
        district: $('#district_en'),
        amphoe: $('#amphoe_en'),
        province: $('#province_en'),
        zipcode: $('#zipcode_en')
    });
});
```

## Author
Name : Khwanchai Kaewyos (LookHin)  
Email : khwanchai@gmail.com

## Website
[www.unzeen.com](https://www.unzeen.com)  
[Facebook](https://www.facebook.com/LookHin)


## License ([MIT](https://opensource.org/licenses/MIT))

Copyright (C) 2019 Khwanchai Kaewyos (LookHin)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
