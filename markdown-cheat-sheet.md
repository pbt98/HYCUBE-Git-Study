# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## 기본 문법

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### 제목 수준

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### 인용문

> blockquote

### 순서 있는 아이템들

1. First item
2. Second item
3. Third item

### 순서 없는 아이템들

- First item
- Second item
- Third item

### 짧은 코드 넣기

`print("HYU ERICA")`

### 구분을 위한 가로선 넣기

---

### 링크

[title](https://www.example.com)

### 이미지 넣기

![alt text](image.jpg)

## 확장된 문법

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### 표

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### 블록 안에 소스코드 넣기

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### 미주

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### 정의 목록

term
: definition

### 취소선

~~The world is flat.~~

### 할 일

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
