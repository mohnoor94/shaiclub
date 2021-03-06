---
title: "Anticipating Heart Failure with ML"
date: 2021-07-22
categories: ["مقالات"]
tags: ["xray", "Image", "Classification", "Computer Vision", "Ai mid"]
cover:
    image: images/anticipating_heart_failure_with_ML.png
    alt: "anticipating_heart_failure_xray"
    caption: "anticipating_heart_failure_xray"
---

كلنا بنعرف أهمية الذكاء الاصطناعي وزيادة الأبحاث والاعتماد عليه بمختلف المجالات 📉

وواحد من المجالات اللي بزيد الطلب فيها على الذكاء الاصطناعي هو الطب 👨‍⚕️

باحثين من معهد MIT طوروا خوارزمية قادرة على اكتشاف درجة احتباس السوائل بالرئة من صورة X-ray واحدة فقط 🤓

احتباس السوائل هو واحد من الأعراض الشائعة لفشل القلب، وتحديد درجة الاحتباس بشكل دقيق بساعد الطبيب على اتخاذ الإجراء المناسب، لكن تحديد الدرجة من صور الX-ray أحياناً بتكون عملية صعبة وبتأدي لتشخيصات غير دقيقة ❌

الباحثين دربوا موديل بالاستعانة بأكثر من 300,000 صورة X-ray مع التقرير المرافق لكل منها، وتم تقسيم التشخيص لأربع مستويات من 0 (صحي) إلى 3 (سيئ جدا) 📋

ومن الملفت للنظر أنه التقارير اللي تم استخدامها لتدريب الموديل غالبها ما احتوى بشكل صريح على ذكر لدرجة الاحتباس! ومع هيك قدر الموديل على تحقيق نتائج مميزة، بحيث قدر على التنبؤ بالدرجة الصحيحة بأكثر من نصف المرات، والتشخيص الصحيح للدرجة الثالثة بدقة 90% 🥳

[لمزيد من التفاصيل](https://news.mit.edu/2020/anticipating-heart-failure-machine-learning-1001)