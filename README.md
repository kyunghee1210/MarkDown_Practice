# Test File
## first test file

# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6

**bold text**
*italicized text*
__bold text__
_italicized text_

> 이순신 장군님께서는 이렇게 말씀하셨다.

# Ordered List
1. apple
2. banana
    - red
    - yello
    - green
3. lemon
9. orange
5. kiwi

# Unordered List
- apple
- banana
    - apple
    - banana
    - lemon
- lemon

This is my `first` file!!

---

# Link
[Google](http://www.google.com)

# Image
![cloud image](cloud.jpg)

# Table
| Syntax | Description | Test |
| ------ | ------ | ----- |
| Header | Title | title |
| Paragraph | Text | title |
| Apple | Banana | title |

# Fenced Code Block
```c
#include <stdio.h>
int main() {
    int number1, number2, sum;

    printf("Enter two integers : ");
    scanf("%d %d", &number1, &number2);

    // caculating sum
    sum = number1 + number2;

    printf("%d + %d = %d", number1, number2, sum);
    return 0
}
```

```javascript
function func() {
    var a = 'AAA'
    return a;
}
```

```css
.list > li {
    position: absolute;
    top: 40px;
}
```

```bash
$ vim ./~zshrc
```

```python 
s = "Python syntax highliting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a tag.
```

# Strikethrough
~~The world is flat.~~

# Task List
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

# Subscript / Superscript
- 19^th^
- H~2~O

# Footnotes
footnote 1 link[^first]
footnote 2 link[^second]

[^first]: Footnote **can have markup language**.
[^second] : Footnote text.

# Definition List
Term 1
:   Definition 1
with lazy continuation.
Term 2
:   Definition 2
        { some code, port ~ }

# Abbreviations
This is HTML abbreviation example.
*[HTML] : Hyper Text Markup.

# Custom Containers
::: warnig
* hare be dragons *
:::

# Imogie
:crying: :smile: :sad: :happy:
8-) :-) :-(


