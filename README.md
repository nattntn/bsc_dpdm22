# bsc_dpdm22
วิชา SC663403 Data Preparation and Data Mining ของ ณัฐนิช หิรัญชวโรจน์

- Midterm (data prepocessing ปฏิบัติ (กลุ่ม))   20%
- Final(ทฤษฎี data mining เดี่ยว)     30%  วันที่ 28 มีค 66 
- Project(data prepocessing + data mining (กลุ่ม))   20%   วันที่ 31 มีค. 66
- Homework(แบ่งกลุ่มใหม่ทุกครั้ง)  20% 
- Quiz(เดี่ยว ถามในห้อง)      10%

# FINAL PROJECT
MEMBERS 
- 8.นายนราวิชญ์ ประทานทรัพย์
- 9.นางสาวภรณกนก ภูผาธรรม
- 18.นางสาวณัฐนิช หิรัญชวโรจน์

[COLAB FINAL PROJECT](https://github.com/natthanich/bsc_dpdm22/blob/main/storke_project.ipynb)

[PRESENTATION FINAL PROJECT](https://github.com/natthanich/bsc_dpdm22/blob/main/Final-Project.pdf)

# Mean absolute percentage error (MAPE)
![image](https://user-images.githubusercontent.com/108257658/219445247-5af7b5b0-a488-4a1c-9db5-4262b35a19d6.png)

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

# Decision Tree
![image](https://user-images.githubusercontent.com/108257658/219439006-b4eeb69d-9a73-4aff-8d13-3ffc0716ea53.png)
## Concept ในการสร้าง 
![image](https://user-images.githubusercontent.com/108257658/219439201-ad570e00-95bb-4d71-b3fb-83d4b4886f7d.png)
## วิธีการสร้าง
![image](https://user-images.githubusercontent.com/108257658/219439581-d84e9adb-1821-47ef-b0b1-c01ed548db92.png)
ตัวอย่าง:https://github.com/natthanich/bsc_dpdm22/blob/692bee60a72fe20f003795b0a7f4d37adbda15c1/HW5_Decision%20Tree.pdf



# รวบรวม code Data Mining
