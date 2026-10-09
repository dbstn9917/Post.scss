# Post 요소

Post.scss는 WHATWG의 **HTML 표준**을 준수하는 문서에서 올바르게 작동할 수 있습니다.  
올바르게 작성된 문서의 예시는 [index.html](../index.html)을 확인해 보세요.

이 페이지에서는 Post 요소의 종류와 올바른 작성 방법을 알아보겠습니다.

## Paragraph

```html
<p>이것은 paragraph 입니다.</p>
```

`<p>` 태그는 **문단**을 작성할 때 사용합니다.

```html
<p>줄바꿈이 필요한 경우<br />이렇게 하시면 됩니다.</p>
```

문단 내에서 줄바꿈이 필요한 경우 `<br>` 태그를 이용해 주세요.

```html
<p>문단1 입니다.</p>
<p>문단2 입니다.</p>
```

각 문단 간의 간격은 `1rem`입니다.

> [!NOTE]
> 대부분의 Post 요소는 `1rem`의 **상하 margin**을 갖고 있습니다.  
> [커스텀 프로퍼티](custom-properties.md)를 이용하면 모든 Post 요소에 적용된 상하 margin을 일괄적으로 수정할 수 있습니다.

## Heading

```html
<h1>이것은 heading 입니다.</h1>
```

`<h1>` ~ `<h6>` 태그는 **제목**을 작성할 때 사용합니다.

```html
<h1>이것은 heading 1 입니다.</h1>
<h2>이것은 heading 2 입니다.</h2>
<h3>이것은 heading 3 입니다.</h3>
<h4>이것은 heading 4 입니다.</h4>
<h5>이것은 heading 5 입니다.</h5>
<h6>이것은 heading 6 입니다.</h6>
```

제목은 1부터 6까지 총 **6단계**로 구분됩니다.

## Text Formatting

**텍스트 서식 요소**는 `<p>` 태그 같은 텍스트를 포함하는 요소 내부에서 사용할 수 있습니다.

### Bold

```html
<p>이것은 <strong>bold</strong> 입니다.</p>
```

`<strong>` 태그를 이용하면 **볼드** 처리할 수 있습니다.

### Italic

```html
<p>이것은 <em>italic</em> 입니다.</p>
```

`<em>` 태그를 이용하면 **이탤릭** 처리할 수 있습니다.

### Strikethrough

```html
<p>이것은 <del>strikethrough</del> 입니다.</p>
```

`<del>` 태그를 이용하면 **취소선** 처리할 수 있습니다.

### Highlight

```html
<p>이것은 <mark>highlight</mark> 입니다.</p>
```

`<mark>` 태그를 이용하면 **하이라이트** 처리할 수 있습니다.
