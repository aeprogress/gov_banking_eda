# Goverment Banking EDA

## Social Development Bank 2017-2022
Social Development Bank dataset is an open source data provided by the Open Data portal of Saudi Arabia initiative. The social funding products are designed to target an important community segment in the Saudi Arabia, the underprivileged citizens, offering them an opportunity to obtain simple and easy loans which enable them to meet necessary obligations

### Get the data here
The data comes from [Social Development Bank](https://data.gov.sa/Data/en/organization/social_development_bank). 

### Data Dictionary



|التعريف |	المتغير |
|:---------|:-----------|
مدينة العميل الذي صرف له القرض	|المدينة
نوع القرض (افراد، اعمال، نقل)|	نوع التمويل
نوع القرض المصروف للعميل	|المنتج
القطاع الذي يعمل فيه العميل|	قطاع العميل
المبلغ المقدم كقرض للعميل|	قيمة التمويل
مبلغ سداد التمويل الشهري	|قيمة القسط
الشهر الذي صرف فيه التمويل|	تاريخ الصرف
ذكر او انثى	|جنس العميل
المرحلة العمرية التي ينتمي لها العميل (شباب، بالغ في منتصف العمر، كبار سن، الخ)	|الفئة العمرية
الحالة الزواجية أو الحالة المدنية للشخص	|الحالة الاجتماعية
هل العميل من ذوي الاحتياجات الخاصة (نعم، لا)|	احتياجات خاصة
العدد التقريبي لأفراد اسرة العميل	|عدد افراد الاسرة
هل القرض ادخاري؟ (نعم، لا)	|قرض ادخاري
الدخل التقريبي الشهري للعميل	|قيمة الدخل
تصنيف الدخل الى مجموعات ما بين (ضعيف، متوسط، مرتفع، الخ)	|نوع الدخل
السنة التي صرف فيها التمويل	|السنة

*For the english description of data refer to the presentation file*



### Goals
- Presenting findings gathered from analysis in a report format.
- Discovering packages and functions in python for data manipulation and EDA.

## Content 

```bash
./
│   README.md
│   
└───data/
│   │   gov_banking_data.csv
│   
└───presentation/
│   │   presentation.pptx
│   
└───src/
    │   preprocessing_concatenation.ipynb
    │   gov_banking_eda.ipynb
```

## Used Libraries
- pandas 
- numpy 
- matplotlib 
- seaborn 
- arabic_reshaper
- bidi.algorithm
- plotly
