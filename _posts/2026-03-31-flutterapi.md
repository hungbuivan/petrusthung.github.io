---
layout: default
title: "Flutter gọi API như thế nào?"
date: 2026-03-31
image: "https://via.placeholder.com/800x400"
tags: [Flutter]
---

## 🚀 Vấn đề
Làm sao để Flutter lấy dữ liệu từ backend?

## 🛠 Cách làm
Sử dụng package http:

```dart
final response = await http.get(Uri.parse("http://localhost:8080/api"));