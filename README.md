# bsc_dpdm22
วิชา SC663403 Data Preparation and Data Mining ของ ณัฐนิช หิรัญชวโรจน์

- Midterm (data prepocessing ปฏิบัติ (กลุ่ม))   20%
- Final(ทฤษฎี data mining เดี่ยว)     30%
- Project(data prepocessing + data mining (กลุ่ม))   20%
- Homework(แบ่งกลุ่มใหม่ทุกครั้ง)  20% 
- Quiz(เดี่ยว ถามในห้อง)      10%

# Mean absolute percentage error (MAPE)
-ค่าสัมบูรณ์ของร้อยละของความคลาดเคลื่อนเฉลี่ย: เป็นการวัดความถูกต้องโดยคำนวณเปอร์เซ็นต์ความผิดพลาดในการพยากรณ์ จึงทำให้ค่านี้ไม่มีหน่วย เหมาะกับการเปรียบเทียบอนุกรมเวลาหลายชุด เมื่อใช้เทคนิคการพยากรณ์เดียวกัน// ยิ่งค่าน้อยยิ่งดี

https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_percentage_error.html?fbclid=IwAR35BB6XKeHluJcbma0TUPOyi8siM5-v9xbJxLWAjlFP4ViULZlSMXgwD34

![image](https://user-images.githubusercontent.com/108257658/207902232-3f6452d4-97ac-48e3-9722-594f81f3c4d6.png)


$Example$
>>> from sklearn.metrics import mean_absolute_percentage_error

>>> y_true = [3, -0.5, 2, 7]

>>> y_pred = [2.5, 0.0, 2, 8]

>>> mean_absolute_percentage_error(y_true, y_pred)

# The Data Visualisation Catalogue
https://datavizcatalogue.com/

โทนสี: https://colorhunt.co/
cmap color: https://matplotlib.org/stable/tutorials/colors/colormaps.html

# Normalization
https://scikit-learn.org/stable/modules/preprocessing.html
เราจะทำการ Normalization ข้อมูลที่เป็นตัวเลขเพื่อปรับมาตรฐานของข้อมูลให้อยู่ในระดับเดียวกัน (มีสเกลเดียวกัน) เพื่อที่ตัวแปรแต่ละตัวแปรจะได้มีน้ำหนักเท่า ๆ กัน Z(0,1)
