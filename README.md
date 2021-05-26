# SEO_TEMPLATE_WEB_HTML
# SEO 메타태그 최적화하기

## 매타테크 최적화하기

- 네이버 키워드 검색 툴을 이용해서 월 검색건 700이하의 키워드를 잡는 것이 좋다.
- Tittle은 70자 이내, 선정한 키워드를 넣는다.
- Description은 80자 이하로 한다.
- keyword 160자내로
- 모바일 최적화
- 웹내 컨텐츠에 키워드를 중간 중간 넣어주는 것이 좋다.

```html
<meta charset="utf-8">

<!-- 모바일 최적화 -->
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

<meta name="author" content="랜딩컴퍼니">

<!-- description 80자내로 -->
<meta name="description" content="랜딩페이지 제작을 해드립니다. 쉽고 빠르고 트랜디하게 랜딩페이지를 제작해드립니다">
<meta property="og:description" content="랜딩페이지 제작을 해드립니다. 쉽고 빠르고 트랜디하게 랜딩페이지를 제작해드립니다">

<!-- 키워드, 160자이내. 메인키워드와 세부키워드를 포함 -->
<meta name="keywords" content="키워드들.."/>

<meta property="og:type" content="website">
<!-- 썸네일 이미지 -->
<meta property="og:image" content="http://www.mysite.com/myimage.jpg">
<!-- 사이트 주소 -->
<meta property="og:url" content="http://www.mysite.com">
<!-- 사이트명 --> 
<meta property="og:site_name" content="사이트명, 내가 생각하는 사이트의 이름을 넣는다">

<!-- 메인 키워드를 포함한 타이틀, 70자내로 작성-->
<title>메인키워드</title>
<meta property="og:title" content="메인키워드">

<!-- App 최적화-->
<meta property="al:ios:url" content="applinks://docs">
<meta property="al:ios:app_store_id" content="12345">
<meta property="al:ios:app_name" content="App Name">
<meta property="al:android:url" content="applinks://docs">
<meta property="al:android:app_name" content="App Name">
<meta property="al:android:package" content="org.applinks">
<meta property="al:web:url" content="https://apppower.com">

<!-- 사이트 주소가 의미하는 것, https://www.website.com/mysite/hello-->
<!-- 즉, 현재의 위치를 의미한다.-->
<link rel="canoncial" href="사이트주소">
```

## References

[https://blog.naver.com/ourbliss90/221870861853](https://blog.naver.com/ourbliss90/221870861853)

[https://blog.naver.com/ourbliss90/221876661964](https://blog.naver.com/ourbliss90/221876661964)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5e0b0443-f693-40d3-aa40-22255b2d6bd1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5e0b0443-f693-40d3-aa40-22255b2d6bd1/Untitled.png)

## **Why does canonicalization matter?**

[Duplicate content](https://moz.com/learn/seo/duplicate-content) is a complicated subject, but when search engines crawl many URLs with identical (or very similar) content, it can cause a number of SEO problems. First, if search crawlers have to wade through too much duplicate content, they may miss some of your unique content. Second, large-scale duplication may dilute your ranking ability. Finally, even if your content does rank, search engines may pick the wrong URL as the "original." Using canonicalization helps you control your duplicate content.

## **The problem with URLs**

You might be thinking "Why would anyone duplicate a page?" and wrongly assume that canonicalization isn’t something you have to worry about. The problem is that we, as humans, tend to think of a page as a concept, such as your homepage. For search engines, though, every unique URL is a separate page. For example, search crawlers might be able to reach your homepage in all of the following ways:

- [http://www.example.com](http://www.example.com/)
- [https://www.example.com](https://www.example.com/)
- [http://example.com](http://example.com/)
- [http://example.com](http://example.com/)/index.php
- [http://example.com](http://example.com/)/index.php?r...

To a human, all of these URLs represent a single page. To a search crawler, though, every single one of these URLs is a unique "page." Even in this limited example, we can see there are five copies of the homepage in play. In reality, though, this is just a small sample of the variations you might encounter.

Modern content management systems (CMS) and dynamic, code-driven websites exacerbate the problem even more. Many sites automatically add tags, allow multiple paths (and URLs) to the same content, and add URL parameters for searches, sorts, currency options, etc. You may have thousands of duplicate URLs on your site and not even realize it.

⇒ canonical을 적용하면 '오리지널 컨텐츠'가 위치하는 곳을 정확하게 찝어준다고 보면 된다.# SEO_TEMPLATE_WEB_HTML
