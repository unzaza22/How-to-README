# How-to-README
วิธีการใช้งาน README
## หัวข้อ(Headings)
#### Syntax:
```
# หัวข้อที่ 1
## หัวข้อที่ 2
### หัวข้อที่ 3
```
#### Output:
# หัวข้อที่ 1
## หัวข้อที่ 2
### หัวข้อที่ 3

## การจัดรูปแบบข้อความ
### อักษรตัวหนา(Bold)
#### Syntax:
```
**ตัวหนา**
```
#### Output:
อักษร**ตัวหนา**

### อักษรตัวเอียง(Italic)
#### Syntax:
```
_ตัวเอียง_
```
#### Output:
อักษร _ตัวเอียง_

### ขีดเส้นกลาง(Strikethrough)
#### Syntax:
```
~~ขึดเส้นกลาง~~
```
#### Output:
ตัวอักษร ~~ขีดเส้นกลาง~~

### ตัวหนาและเอียงบ้างตัวอักษร(Bold and nested italic)
#### Syntax:
```
**ตัวหนาและ_เอียง_**
```
#### Output:
**ตัวหนาและ _เอียง_**

### ตัวหนาและเอียงทั้งหมด(All bold and italic)
#### Syntax:
```
***ตัวหนาและเอียง***
```
#### Output:
***ตัวหนาและเอียง***

### ตัวอักษรห้อย(Subscript)
#### Syntax:
```
ตัวอักษร<sub>ห้อย</sub>
```
#### Output:
ตัวอักษร<sub>ห้อย</sub>

### ตัวอักษรยกกำลัง(Superscript)
#### Syntax:
```
ตัวอักษร<sup>ยกกำลัง</sup>
```
#### Output:
ตัวอักษร<sup>ยกกำลัง</sup>

### ขีดเส้นใต้ตัวอักษร(Underline)
#### Syntax:
```
<ins>ขีดเส้นใต้</ins>
```
#### Output:
<ins>ขีดเส้นใต้</ins>

## การอ้างอิ้งข้อความ(Quoting text)
#### Syntax:
```
>อ้างอิ้ง
```
#### Output:
>อ้างอิ้ง

## การอ้างอิ้งโค้ด
#### Syntax:
```
`อ้างโค้ด`
```
#### Output:
`อ้างโค้ด`

#### Syntax:
````
```
อ้างโค้ด
อ้างโค้ด 
อ้างโค้ด
```
````
#### Output:
```
อ้างโค้ด
อ้างโค้ด
อ้างโค้ด
```

## รองรับการใช้โค้ดสี
#### Syntax:
```
HEX: `#RRGGBB`     `#0969DA`
RGB: `#rgb(R,G,B)` `rgb(9,105,218)`
HSL: `hsl(H,S,L)`  `hsl(212,92%,45%)`
```
#### Output:
|Color|   Syntax     |    Example         |
|:----|:------------:|:------------------:|
|HEX  | `#RRGGBB`    | `#0969DA`          |
|RGB  | `#rgb(R,G,B)`| `rgb(9,105,218)`   |
|HSL  | `hsl(H,S,L)` | `hsl(212,92%,45%)` |

## ลิงค์(Link)
#### Syntax:
```
[Facebook](https://www.facebook.com/apisit.chatsuwan)
```
#### Output:
[Facebook](https://www.facebook.com/apisit.chatsuwan)

## ลิงค์หัวข้อ(Section links)
#### Syntax:
```
[Link Text](#How-to-README)
```
#### Output:
[Link Text](#How-to-README)

## ลิงค์ไฟล์(Relative links)
#### Syntax:
```
[Test relative links](RELATIVE.md) // /,./,../ ใช้งานได้
```
#### Output:
[Test relative links](RELATIVE.md)

## ลิงค์แบบกำหนดเอง(Custom anchors)
#### Syntax:
```
<a name="custom-anchors"></a>
[Link custom anchors](#custom-anchors)
```
#### Output:
<a name="custom-anchors"></a>
[Link custom anchors](#custom-anchors)

## เว้นบรรทัด(Line breaks)
#### Syntax:
```
<br/> 
```
#### Output:
a<br/><br/>b<br/><br/><br/>c

## รูปภาพ(Images)
#### Syntax:
```
![Github logo](https://cdn1.vc4a.com/media/2021/08/github-logo.jpg) // สามารถใช้งานเป็น path ได้ด้วย /assets/images/electrocat.png
```
#### Output:
![Github logo](https://cdn1.vc4a.com/media/2021/08/github-logo.jpg)

## รายการ(Lists)
#### Syntax:
```
- รายการ
* รายการ
+ รายการ
1. รายการ
2. รายการ
3. รายการ
```
#### Output:
- รายการ
* รายการ
+ รายการ
1. รายการ
2. รายการ
3. รายการ

## รายการซ้อนกัน(Nested Lists)
#### Syntax:
```
1. รายการ
   - รายการซ้อน 1
     - รายการซ้อน 2
```
#### Output:
1. รายการ
   - รายการซ้อน 1
     - รายการซ้อน 2

## เช็คบล็อก(Task lists)
#### Syntax:
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] \(Optional) checkbox // ถ้าจะใช้วงเล็บให้ขึ้นด้วย \

```
#### Output:
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] \(Optional) checkbox

## การกล่างถึงหรือแท็ก(Mentioning people and teams)
#### Syntax:
```
@github/support
```
#### Output:
@github/support Not think.

## การอ้างอิ้งปัญหาและรีเควส(Referencing issues and pull requests)
#### Syntax:
```
#26 // ใช้ได้โดยการใช้ #
```
#### Output:
#26

## การอ้างอิ้งแหล่งข้อมูลภายนอก(Referencing external resources)
[Link](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/configuring-autolinks-to-reference-external-resources)

## อัพโหลดอุปกรณ์
สามารถ upload รูปภาพโดย drag หรือใช้ link จาก browser
สามารถ upload รูปภาพ ใน issue, pull requests, comments, and `.md` ไฟล์ได้

## ใช้ emojis ได้(Using emojis)
[Emojis code](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

## ย่อหน้า(Paragraphs)
ย่อหน้าได้โดยการเว้นบรรทัดว่างระหว่างข้อความ

## Footnote
#### Syntax:
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```
#### Output:
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## คำเตือน(Alert)
#### Syntax:
```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
#### Output:
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## คอมเมนต์แบบซ่อน(Hiding content with comments)
#### Syntax:
```
<!-- comment -->
```
#### Output:
<!-- comment -->

## ละเว้นการใช้ markdown(Ignoring Markdown formatting)
#### Syntax:
```
ละเว้น markdown \*ตัวหนา\* กับ \*ตัวหนา\*. // ใช้ \ ก่อนสัญลักษณ์ markdown
```
#### Output:
Let's rename \*our-new-project\* to \*our-old-project\*.
[markdown syntax](https://daringfireball.net/projects/markdown/syntax#backslash)

## ปิดการใช้งาน markdown
![Disable Markdown](https://docs.github.com/assets/cb-11496/mw-1440/images/help/writing/display-markdown-as-source-global-nav-update.webp)
