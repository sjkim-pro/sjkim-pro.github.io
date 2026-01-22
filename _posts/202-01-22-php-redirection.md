---
title: "php redirection"
date: 2026-01-22
categories: 
  - dev
  - php
tags: [dev, php, backend, webserver]
---
운영하던 페이지를 다른 도메인으로 redirect 시키는 방법

```php
// 1. 이동할 URL 설정
$redirect_url = "https://www.example.com";

// 2. 리다이렉트 헤더 전송
header ("Location: {$redirect_url}");
exit; // 하단 코드가 실행되지 않도록 여기에서 종료

// 원래 실행하던 코드들
```