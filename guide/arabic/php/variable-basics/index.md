---
title: PHP Variable Basics
localeTitle: أساسيات PHP المتغيرة
---
المتغيرات تسمح للمبرمجين باستخدام البيانات throuhgout a PHP script.

في PHP ، تبدأ المتغيرات دائمًا برمز `$` متبوعًا باسم المتغير. فقط الحروف والأرقام (قد لا تكون الحرف الأول) والشرطات السفلية يمكن أن تشكل اسم متغير.

على سبيل المثال ، `$my_variable` `$anotherVariable` و `$the2ndVariable` و `$the2ndVariable` أسماء متغيرات صالحة.

أسماء المتغيرات حساسة لحالة الأحرف. `$my_variable` عن `$My_Variable` وهو يختلف عن `$mY_vARiAblE` .

قبل استخدام المتغير ، يجب أن يكون له قيمة معينة له.

 `    <?php 
    $my_number = 1; 
    echo($my_number); 
 
    >>> 1 
` 

في المثال أعلاه ، المتغير هو `$my_number` . القيمة المسندة إليه كانت الرقم `1` . ثم تم تمرير المتغير كمعلمة لوظيفة `echo` ، والتي تخرج القيمة إلى سطر الأوامر.