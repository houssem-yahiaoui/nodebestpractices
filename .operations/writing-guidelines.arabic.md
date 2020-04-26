# Our content writing manifest

.كيف نعزز تجربة القراءة والتعلم لزوارنا

## 1. البساطة أفضل

مهمتنا هي تسهيل قراءة المعرفة واستيعابها، فنحن ننظم المحتوى. على هذا النحو، نركز على تحويل الموضوعات المعقدة
والمستنفدة إلى قائمة مبسطة، والتجارة بالمعلومات الزائدة مع تفاصيل أقصر وأقل دقة، وتجنب الموضوعات القابلة
.للاشتعال" والمثيرة للجدل والهروب من الأفكار الذاتية لصالح الممارسات المقبولة بشكل عام"

## 2. كن مستندًا إلى أدلة وبراهين

يجب أن يثق قراؤنا بدرجة كبيرة في أن المحتوى الذي يتصفحونه موثوق به. نحقق ذلك من خلال تضمين أدلة مثل المراجع 
والبيانات والموارد الأخرى المتاحة لهذا الموضوع. عمليا، اسعَ إلى تضمين اقتباسات من مصادر موثوقة، أو عرض 
.معايير، أو أنماط تصميم ذات صلة، أو أي مقياس علمي لإثبات ادعاءاتك 


## 3. MECE (Mutually Exclusive and Collectively Exhaustive)

بصرف النظر عن المحتوى الذي يتم تحريره وموثوق به إلى حد كبير ، يجب أن يتوفر التصفح  تغطية كاملة 
.للموضوع. لا ينبغي استبعاد أي موضوع فرعي مهما كانت نسبية أهميته


## 4. التنسيق الثابت 

يتم تقديم المحتوى باستخدام نماذج ثابتة. يجب أن يتوافق أي محتوى مستقبلي مع نفس النموذج. إذا كنت ترغب في إضافة 
رموز نقطية جديدة ، قم بنسخ تنسيق رمز نفطي  موجود وقم باستخذامه لتغطية احتياجاتك. لمزيد من المعلومات يرجى 
الاطلاع على هذا 
[النموذج](https://github.com/i0natan/nodebestpractices/blob/master/sections/template.md).

## 5. It's About Node.js
## 5. حول Node.js

Each advice should be related directly to Node.js and not to software development in general. When we advise to implement generic pattern/rule in Node.js, the content should focus on the Node implementation. For example, when we advise to sanitize all requests input for security reasons, Node-lingo should be used - ‘Use middleware to sanitize request input’. If an item has no specific implementation in Node.js (e.g. it looks the same in Python & Jaba) - include it within a generic container item, see item 6.5 for example.

يجب أن تكون كل نصيحة مرتبطة مباشرة بـ Node.js وليس بتطوير البرمجيات بشكل عام. عندما ننصح بتنفيذ النمط / القاعدة العامة في Node.js ، يجب أن يركز المحتوى على تنفيذ العقدة. على سبيل المثال ، عندما ننصح بتعقيم جميع طلبات الإدخال لأسباب أمنية ، يجب استخدام Node-lingo - "استخدام البرامج الوسيطة لتعقيم إدخال الطلبات". إذا لم يكن للعنصر تطبيق محدد في Node.js (على سبيل المثال ، يبدو متشابهًا في Python & Jaba) - قم بتضمينه في عنصر حاوية عام ، راجع العنصر 6.5 على سبيل المثال.

## 6. Leading vendors only
## 6. كبار البائعين فقط

Sometimes it's useful to include names of vendors that can address certain challenges and problems like npm packages, open source tools or even commercial products. To avoid overwhelmingly long lists or recommending non-reputable and unstable projects, we came up with the following rules:
في بعض الأحيان يكون من المفيد تضمين أسماء البائعين التي يمكنها معالجة تحديات ومشاكل معينة مثل حزم npm أو أدوات مفتوحة المصدر أو حتى المنتجات التجارية. لتجنب القوائم الطويلة للغاية أو التوصية بمشاريع غير حسنة السمعة وغير مستقرة ، توصلنا إلى القواعد التالية:

- Only the top 3 vendors should be recommended – a vendor that appears in the top 3 results of a search engine (Google or GitHub sorted by popularity) for a given relevant keyword can be included in our recommendation.
- يجب التوصية فقط بأفضل 3 بائعين - يمكن تضمين البائع الذي يظهر في أعلى 3 نتائج لمحرك بحث (يتم ترتيب Google أو GitHub حسب الشعبية) لكلمة رئيسية معينة ذات صلة في توصيتنا.
- If it’s a npm package it must also be downloaded at least 750 times a day on average.
- إذا كانت حزمة npm ، فيجب أيضًا تنزيلها 750 مرة على الأقل في المتوسط ​​يوميًا.
- If it’s an open-source project, it must have been updated at least once in the last 6 months.
- إذا كان مشروعًا مفتوح المصدر ، فيجب تحديثه مرة واحدة على الأقل في آخر 6 أشهر.
