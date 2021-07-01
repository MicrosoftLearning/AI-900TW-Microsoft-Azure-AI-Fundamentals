---
title: 线上託管指示
permalink: index.html
layout: home
---

# Azure AI Fundamentals 練習

此存放庫包含適用於 Microsoft 課程的實作教室練習 [AI-900 *Microsoft Azure 人工智慧*](https://docs.microsoft.com/zh-tw/learn/certifications/courses/ai-900t00) 和 Microsoft Learn 等效自學型課程模組：[開始 Azure 上的人工智慧](https://docs.microsoft.com/learn/paths/get-started-with-artificial-intelligence-on-azure/)，[使用 Azure Machine Learning 建立無程式碼預測模型](https://docs.microsoft.com/zh-tw/learn/paths/create-no-code-predictive-models-azure-machine-learning/)，[探索 Microsoft Azure 中的電腦視覺](https://docs.microsoft.com/learn/paths/explore-computer-vision-microsoft-azure/)，[探索自然語言處理](https://docs.microsoft.com/learn/paths/explore-natural-language-processing/)和[探索交談 AI](https://docs.microsoft.com/learn/paths/explore-conversational-ai/)。此練習是為了配合學習材料並讓您使用其描述的技術進行練習而設計。 

您將需要 Microsoft Azure 訂用帳戶，以完成這些練習。若您的講師沒有為您提供 Microsoft Azure 訂用帳戶，您可以在 [https://azure.microsoft.com](https://azure.microsoft.com) 註冊免費試用版。

{% assign labs = site.pages | where_exp:"page", "page.url contains '/instructions'" %}
| Exercises |
| ------- | 
{% for activity in labs  %}| [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
