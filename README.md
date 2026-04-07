# data-analysis
Data analysis project on a diabetes dataset including data cleaning, handling missing values using median imputation, outlier detection and treatment using IQR method, and exploratory data analysis with visualizations.
# Diabetes Data Analysis

## الهدف
تحليل بيانات مرض السكري لفهم العوامل المؤثرة في الإصابة بالمرض، ودراسة العلاقات بين المتغيرات مثل العمر، مؤشر كتلة الجسم (BMI)، ومستوى الجلوكوز.

## Dataset
تم استخدام مجموعة بيانات خاصة بمرض السكري تحتوي على المتغيرات التالية:
- Glucose
- Blood Pressure
- BMI
- Insulin
- Age
- Outcome (تشخيص الإصابة بالسكري)

رابط البيانات:
https://t.ly/temdJ
---

## خطوات العمل

### 1. تنظيف البيانات (Data Cleaning)
- معالجة القيم المفقودة باستخدام median
- استبدال القيم غير المنطقية (مثل القيم 0)

### 2. معالجة القيم المتطرفة (Outliers)
- استخدام طريقة IQR لاكتشاف القيم المتطرفة
- التعامل معها لتحسين جودة البيانات

### 3. التحليل الاستكشافي (EDA)
- تحليل إحصائي للبيانات
- دراسة العلاقات بين المتغيرات
- مقارنة بين المصابين وغير المصابين
### 4. Visualization
- Boxplot: العلاقة بين العمر والإصابة بالسكري  
- Bar Chart: مقارنة الإصابة بين الرجال والنساء  
- Regression Plot: العلاقة بين BMI و Glucose  

---
## أهم النتائج

- تزداد احتمالية الإصابة بالسكري مع التقدم في العمر  
- يوجد ارتباط بين ارتفاع BMI وارتفاع مستوى الجلوكوز  
- اختلاف في نسب الإصابة بين الجنسين  
- وجود قيم غير منطقية في البيانات تم معالجتها
- Glucose was the most influential feature
Zero values in some features were unrealistic and needed handling
Data cleaning improved data quality significantly 

---

## الأدوات المستخدمة
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
