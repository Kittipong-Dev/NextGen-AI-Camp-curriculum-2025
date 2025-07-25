# Table of Contents

Week 1:

- [Python #1](#python-1)
- [การใช้งาน Google Colab](#การใช้งาน-google-colab)
- [Python #2](#python-2)
- [Introduction to AI, ML, DL](#introduction-to-ai-ml-dl)
- [NumPy](#numpy)

Week 2:

- [Python #3](#python-3)
- [Python #4](#python-4)
- [Neural Network #1](#neural-network-1)
- [Matplotlib](#matplotlib)

Week 3:

- [Neural Network #2](#neural-network-2)
- [Pandas](#pandas)
- [PyTorch](#pytorch)

Week 4:

- [Neural Network #3](#neural-network-3)
- [OpenCV #1](#opencv-1)
- [OpenCV #2](#opencv-2)
- [Applying Neural Networks to Tabular Data](#applying-neural-networks-to-tabular-data)

Week 5:

- [CNN #1](#cnn-1)
- [CNN #2](#cnn-2)
- [TorchVision](#torchvision)
- [CNN Transfer Learning](#transfer-learning)

Week 6:

- [การจำแนกเสียงด้วย Convolutional Neural Networks](#การจำแนกเสียงด้วย-convolutional-neural-networks)
- [การระบุตัวผู้พูดโดยใช้ระดับเสียงและ MFCC](#การระบุตัวผู้พูดโดยใช้ระดับเสียงและ-mfcc)

Week 7:
- [Effective Deep Network Architecture (การออกแบบสถาปัตยกรรมโครงข่ายเชิงลึกอย่างมีประสิทธิภาพ)](#effective-deep-network-architecture)

Workshop:
- [Workshop : การประเมินราคาเสื้อผ้ามือสอง](#workshop-การประเมินราคาเสื้อผ้ามือสอง)
---

## Week 1:

### Python #1

ในหัวข้อนี้ จะเริ่มต้นด้วยการติดตั้ง Python และการตั้งค่าในระบบต่าง ๆ ต่อมาจะเรียนรู้เกี่ยวกับการรับและแสดงผลข้อมูล (I/O) รวมถึงการทำงานกับประเภทข้อมูลพื้นฐาน (datatype) และตัวแปร (variables) เพื่อจัดเก็บข้อมูล นอกจากนี้ยังจะครอบคลุมการดำเนินการทางคณิตศาสตร์ (math operations) เบื้องต้น ซึ่งเป็นพื้นฐานที่สำคัญในการเขียนโปรแกรมและการแก้ปัญหาทางคอมพิวเตอร์

- Video: [NextGenAI-2025 | Python #1](https://youtu.be/Yizq4I6JThY?si=vOa8_ghIGK5pN9b2)
- Code: [NextGen_AI_Camp_Python#1.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%231/Python%231/NextGen_AI_Camp_Python%231.ipynb)

### การใช้งาน Google Colab

ในหัวข้อนี้ เราจะเรียนรู้การใช้งาน Google Colab ซึ่งเป็นเครื่องมือสำหรับการเขียนและรันโค้ด Python บนคลาวด์ ผู้เรียนจะได้เรียนรู้วิธีการตั้งค่าและใช้ทรัพยากรจาก Google Colab เช่น การเลือกใช้ CPU หรือ GPU เพื่อเพิ่มประสิทธิภาพการประมวลผล นอกจากนี้ยังจะได้เรียนรู้เกี่ยวกับการใช้ Jupyter Notebook ซึ่งเป็นเครื่องมือที่สำคัญสำหรับนักพัฒนาและนักวิจัย

- Video: [NextGenAI-2025 | Google Colab](https://youtu.be/znOQg9Ax42Q?si=IcBDYol6IHL1gVri)
- Code: [NextGen_AI_Camp_Google_Colab.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%231/Google_Colab/NextGen_AI_Camp_Google_Colab.ipynb)

### Python #2

ในหัวข้อนี้ เราจะเน้นการเขียนโค้ดที่มีเงื่อนไข (conditions) ซึ่งเป็นส่วนสำคัญในการตัดสินใจของโปรแกรม รวมถึงการใช้ตัวดำเนินการตรรกศาสตร์ (logical operators) สำหรับการตรวจสอบเงื่อนไขต่าง ๆ นอกจากนี้ยังจะได้เรียนรู้เกี่ยวกับการใช้ลิสต์ (lists) สำหรับการจัดเก็บและจัดการกลุ่มข้อมูล รวมถึงการจัดการกับสตริง (strings) ซึ่งเป็นข้อมูลประเภทข้อความที่ใช้บ่อยในโปรแกรม

- Video: [NextGenAI-2025 | Python #2](https://youtu.be/7SmFEwKcbTA)
- Code: [NextGen_AI_Camp_Python#2.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%231/Python%232/NextGen_AI_Camp_Python%232.ipynb)

### Introduction to AI, ML, DL

ในหัวข้อนี้ เราจะเริ่มต้นด้วยการแนะนำเกี่ยวกับปัญญาประดิษฐ์ (AI) ซึ่งเป็นการพัฒนาระบบคอมพิวเตอร์ให้สามารถทำงานที่ต้องใช้ความฉลาดของมนุษย์ นอกจากนี้ยังเรียนรู้เรื่องของ Machine Learning ซึ่งเป็นการใช้ข้อมูลและอัลกอริธึมเพื่อให้คอมพิวเตอร์เรียนรู้จากประสบการณ์ รวมถึง Deep Learning ซึ่งเป็นการสร้างโมเดลที่ซับซ้อนและมีความสามารถในการรับรู้และประมวลผลข้อมูลที่ซับซ้อนยิ่งขึ้น จะได้เห็นถึงความเหมือนและความต่างของทั้งสามแนวคิดนี้ รวมถึงแอพพลิเคชันที่นำไปใช้ในโลกจริง

- Video: [Introduction to AI, ML, DL](https://youtube.com/playlist?list=PLnDwFN2GE8GIZGbqWfCapbwQFcXnL9vsA&si=nWkr3v6Z-ILdPXSe)
- Slide: [Introduction to AI, ML, DL](https://docs.google.com/presentation/d/1vKFInRRmAoWwwVsu4yFr9YeDIASOqNjCK_bzeeHfm0k/edit?usp=sharing)

### Numpy

ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับ NumPy ซึ่งเป็นไลบรารีสำคัญใน Python สำหรับการคำนวณเชิงตัวเลข เริ่มต้นด้วยการทำความเข้าใจว่า NumPy คืออะไรและวิธีการสร้างอาร์เรย์ NumPy เรียนรู้การทำงานกับรูปร่างของอาร์เรย์ (shape) การตัดส่วนของอาร์เรย์ (slice) และการใช้ฟังก์ชันต่าง ๆ ของ NumPy รวมถึงการสร้างอาร์เรย์ที่ประกอบด้วยค่าเริ่มต้น เช่น zeros และ ones การสร้างค่าแบบสุ่ม (random) และการใช้ฟังก์ชัน arange ในการสร้างลำดับข้อมูล นอกจากนี้ จะได้เรียนรู้การปรับเปลี่ยนรูปร่างของอาร์เรย์ด้วยฟังก์ชัน reshape และ resize การทำให้อาร์เรย์แบนราบด้วย flatten และการสลับแกนของอาร์เรย์ด้วย transpose การใช้ฟังก์ชันทางสถิติ เช่น mean, median, standard deviation การคำนวณผลคูณจุด (dot product) การต่ออาร์เรย์ด้วย concatenate และการซ้อนอาร์เรย์ด้วย stack สุดท้าย จะได้เรียนรู้การโหลดและบันทึกข้อมูล NumPy ด้วยฟังก์ชัน load และ save เพื่อช่วยให้สามารถจัดการและใช้ประโยชน์จากข้อมูลได้อย่างมีประสิทธิภาพ

- Video: [NextGenAI-2025 | Numpy #1](https://www.youtube.com/watch?v=yVS3yHCMwe0)\
        [NextGenAI-2025 | Numpy #2](https://www.youtube.com/watch?v=YjqnYpRbiOE)
- Code: [NextGen_AI_Camp_Numpy_1_2.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%231/Numpy/NextGen_AI_Camp_Numpy_1_2.ipynb)

---
## Week 2:

### Python #3

ในหัวข้อนี้ เราจะเจาะลึกการใช้งานลิสต์ (lists) ซึ่งเป็นโครงสร้างข้อมูลที่สำคัญในการจัดเก็บและจัดการกลุ่มของข้อมูล โดยจะได้เรียนรู้วิธีการสร้าง การเข้าถึงข้อมูล การปรับปรุงข้อมูลในลิสต์ รวมถึงการใช้งานเมธอดต่าง ๆ ของลิสต์ นอกจากนี้เราจะสำรวจการจัดการกับสตริง (strings) ซึ่งเป็นข้อมูลประเภทข้อความที่ใช้ในหลายๆ โปรแกรม ได้เรียนรู้วิธีการจัดการและการใช้งานฟังก์ชันต่าง ๆ ที่เกี่ยวกับสตริง

- Video: [NextGenAI-2025 | Python #3](https://www.youtube.com/watch?v=-jE0re3eopc)
- Code: [NextGen_AI_Camp_Python#3.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%232/Python%233/NextGen_AI_Camp_Python%233.ipynb)

### Python #4

ในหัวข้อนี้ เราจะเน้นการทำงานกับลูป (loops) ซึ่งเป็นโครงสร้างที่ช่วยให้เราสามารถทำงานที่ต้องทำซ้ำ ๆ ได้ง่ายขึ้น ได้เรียนรู้วิธีการใช้งานลูปชนิดต่าง ๆ เช่น for loop และ while loop นอกจากนี้เรายังจะครอบคลุมการเขียนฟังก์ชัน (functions) ซึ่งช่วยในการจัดโครงสร้างโค้ดให้เป็นระเบียบและสามารถนำกลับมาใช้ใหม่ได้อย่างมีประสิทธิภาพ สุดท้ายเราจะสำรวจการสร้างและใช้งานคลาส (classes) ซึ่งเป็นพื้นฐานของการเขียนโปรแกรมเชิงวัตถุ (OOP) เพื่อสร้างวัตถุ (objects) ที่มีคุณสมบัติและพฤติกรรมต่าง ๆ

- Video: [NextGenAI-2025 | Python #4](https://www.youtube.com/watch?v=HS5fKKy3Wyw&t=466s)
- Code: [NextGen_AI_Camp_Python#4.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%232/Python%234/NextGen_AI_Camp_Python%234.ipynb)

### Neural Network #1
ในหัวข้อนี้ เราจะเริ่มต้นด้วยการทำความเข้าใจพื้นฐานของโครงข่ายประสาทเทียม (ANN) ซึ่งเป็นรากฐานของเทคโนโลยีการเรียนรู้เชิงลึก (Deep Learning) โดยจะได้เรียนรู้เกี่ยวกับส่วนประกอบของ neuron ซึ่งเป็นหน่วยประมวลผลพื้นฐานของ ANN นอกจากนี้ยังจะครอบคลุมการประมาณค่าแบบเชิงเส้น (linear approximation) ซึ่งเป็นขั้นตอนสำคัญในการเรียนรู้ของโครงข่ายประสาท การเรียนรู้เกี่ยวกับ loss function ซึ่งใช้ในการวัดความผิดพลาดของโมเดล และกระบวนการ gradient descent ซึ่งเป็นวิธีการในการปรับพารามิเตอร์ของโมเดลเพื่อให้ได้ค่าที่เหมาะสมที่สุด สุดท้ายเราจะสำรวจวิธีการ visualize ข้อมูลเพื่อให้เข้าใจและวิเคราะห์ผลลัพธ์ได้ง่ายขึ้น

- Video: [NextGenAI-2025 | Neural Network #1](https://www.youtube.com/watch?v=Gmy4jYkcgOA)
- Code: [NextGen_AI_Camp_Neural_Network1.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%232/NN%231/NextGen_AI_Camp_Neural_Network1.ipynb)

### Matplotlib

ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับ Matplotlib ซึ่งเป็นไลบรารีที่สำคัญสำหรับการสร้างกราฟและการแสดงข้อมูลใน Python เริ่มต้นด้วยการทำความเข้าใจว่า Matplotlib คืออะไรและวิธีการสร้างกราฟพื้นฐาน (Basic Chart) และกราฟเส้น (Line Chart) รวมถึงการตั้งชื่อแกน x (xlabel) และแกน y (ylabel) การสร้างกราฟแท่ง (Bar Chart) และการบันทึกกราฟลงไฟล์ (Save chart to file) จะได้เรียนรู้การปรับแต่งลักษณะเส้น (Line Style) การเพิ่มชื่อกราฟ (Title) และคำอธิบายกราฟ (Legend Function) นอกจากนี้จะครอบคลุมการสร้างกราฟกระจาย (Scatter Plots) การเลือกสีและเครื่องหมาย (Color and Marker) และการสร้างฮิสโตแกรม (Histogram) สุดท้ายจะได้เรียนรู้การ Plotting in real time และการสร้าง confusion matrix เพื่อวิเคราะห์ผลลัพธ์ของโมเดล

- Video: [NextGenAI-2025 | Matplotlib](https://www.youtube.com/watch?v=CwbLB9U-MH0)
- Code: [NextGen_AI_Camp_Matplotlib.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%232/Matplotlib/NextGen_AI_Camp_Matplotlib.ipynb)

---
## Week 3:

### Neural Network #2
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับโครงข่ายประสาทเทียมแบบหลายชั้น (Multi-Layer Neural Network) ซึ่งเป็นโครงสร้างพื้นฐานที่ทำให้โมเดลสามารถเรียนรู้รูปแบบที่ซับซ้อนได้ จะได้ทำความเข้าใจการประมาณค่าแบบ Non Linear ซึ่งช่วยให้โมเดลสามารถจับความสัมพันธ์ที่ซับซ้อนระหว่างข้อมูลได้ดีขึ้น นอกจากนี้จะเรียนรู้เกี่ยวกับวงรอบของการสอน AI (Training Loop) ซึ่งประกอบด้วยการปรับปรุงพารามิเตอร์ของโมเดลในแต่ละขั้นตอนการสอน และ Backpropagation ซึ่งเป็นกระบวนการในการคำนวณและปรับปรุงค่าความผิดพลาด (error) ผ่านการปรับน้ำหนักของเครือข่าย จะได้เรียนรู้เกี่ยวกับ Activation Function ซึ่งเป็นฟังก์ชันที่ใช้ในแต่ละนิวรอนเพื่อเพิ่มความสามารถในการเรียนรู้ของโมเดลนอกจากนี้ยังจะครอบคลุมการวัดประสิทธิภาพของโมเดลเพื่อประเมินผลการเรียนรู้ และการทดสอบและปรับแต่ง (Fine Tune) โมเดล Neural Network แบบง่ายเพื่อให้ได้ผลลัพธ์ที่ดีที่สุด

- Video: [NextGenAI-2025 | Neural Network #2 ep.1](https://youtu.be/a1eyTeB93ek?si=guEYvRaRLthcoj0H)<br>
        [NextGenAI-2025 | Neural Network #2 ep.2](https://youtu.be/MOak_Pd7ZzU?si=EM8_XbhYVMLX9x4J)<br>
        [NextGenAI-2025 | Neural Network #2 ep.3](https://youtu.be/lUNoVyyA2ec?si=nNoRyOKKwNag9ChB)
- Code: [NextGen_AI_Camp_Neural_Network2.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%233/NN%232/NextGen_AI_Camp_Neural_Network2.ipynb)

### Pandas
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับ Pandas ซึ่งเป็นไลบรารีสำคัญใน Python สำหรับการจัดการและวิเคราะห์ข้อมูล เริ่มต้นด้วยการทำความเข้าใจ DataFrame ซึ่งเป็นโครงสร้างข้อมูลหลักใน Pandas และวิธีการสร้างและใช้งาน DataFrame จากนั้นจะได้เรียนรู้การอ่านและเขียนข้อมูลจากและไปยังไฟล์ในรูปแบบต่าง ๆ เช่น xlsx และ json นอกจากนี้จะได้เรียนรู้เกี่ยวกับชนิดข้อมูล (Data Type) และวิธีการตรวจสอบข้อมูลด้วยฟังก์ชัน info รวมถึงการใช้ indexing เพื่อเข้าถึงและจัดการข้อมูล จะได้ทำความเข้าใจกับวิธีการจัดการกับข้อมูลที่หายไป (missing data) ด้วยการลบ (Drop) การเติม (Fill) และการแทนที่ (Replace) ข้อมูล สุดท้ายจะครอบคลุมการลบข้อมูลที่ซ้ำซ้อน (Drop duplicate) เพื่อให้ DataFrame มีความถูกต้องและมีคุณภาพมากขึ้น

- Video: [NextGenAI-2025 | Pandas](https://youtu.be/Y7mDtsdtZCU)
- Code: [NextGen_AI_Camp_Pandas.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%233/Pandas/NextGen_AI_Camp_Pandas.ipynb)

### PyTorch
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับ Pytorch และการใช้งาน tensors ซึ่งเป็นโครงสร้างข้อมูลหลักใน Pytorch รวมถึง ndim, item, และ shape ของ tensors การสร้าง random tensors, zero tensors และ one tensors การใช้ arange, การจัดการ datatype และ dtype การดำเนินการทางคณิตศาสตร์พื้นฐาน เช่น add, sub, multiply, divide, matrix mul การหา max, min, mean, sum ของ tensors การใช้ argmax และ argmin การปรับรูปร่างของ tensors ด้วย reshape และ view รวมถึงการ stack และ indexing การสร้าง tensors จาก NumPy ด้วย from_numpy และการแปลง tensors เป็น NumPy ด้วย .numpy

- Video: [NextGenAI-2025 | Pytorch #1](https://youtu.be/9QkuU5RSuT8)
- Code: [NextGen_AI_Camp_PyTorch.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%233/PyTorch/NextGen_AI_Camp_PyTorch.ipynb)
---

## Week 4:

### Neural Network #3
ในหัวข้อนี้ จะได้เรียนรู้การสร้าง Model Neural Network โดยใช้ Pytorch กับ Dataset จริง ตั้งแต่การเตรียมและแบ่งข้อมูลเพื่อโหลดเข้า Model การสร้าง Model โดยใช้ Pytorch รวมถึงเทคนิคการ Train Model แบบต่างๆ การนำ Model ที่สร้างไปใช้งานจริง วิธีการ Save และ Load Model เพื่อใช้งานต่อไป การประเมินผลโมเดลในหลายรูปแบบ การจัดการกับปัญหา Overfit ด้วยเทคนิคต่างๆ เช่น Dropout และ Regularization และการทำ Data Augmentation เพื่อเพิ่มประสิทธิภาพของ Model

- Video: [NextGenAI-2025 | Neural Network #3 ep.1](https://youtu.be/MnLQoaPt0wg)<br>
        [NextGenAI-2025 | Neural Network #3 ep.2](https://youtu.be/pUBjMdU6PHU)<br>
        [NextGenAI-2025 | Neural Network #3 ep.3](https://youtu.be/jdjrZ38Lw18)<br>
        [Loss Function](https://www.youtube.com/watch?v=h1XjpBmmJ_s)<br>
        [Backpropagation](https://www.youtube.com/watch?v=Pes6YYEIDno)
- Code: [NextGen_AI_Camp_Neural_Network3.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%234/NN%233/NextGen_AI_Camp_Neural_Network3.ipynb)

### OpenCV #1
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับ OpenCV ซึ่งเป็นไลบรารีสำคัญสำหรับการประมวลผลภาพ (image processing) เริ่มต้นด้วยการทำความเข้าใจโครงสร้างจุดภาพ (Pixel) และการจัดเรียงจุดสี (Color pixel) รวมถึงระบบสีต่าง ๆ เช่น RGB และ Gray จะได้เรียนรู้การสร้างอะเรย์ภาพ การเปิดไฟล์ภาพและการบันทึกภาพ นอกจากนี้ จะทำความเข้าใจคุณสมบัติความละเอียดของภาพ (Resolution) และการปรับขนาดภาพ (Resize) รวมถึงการควอนไทซ์ (Quantize) และการจัดการกับ Bit depth การตรวจจับสี (Color detection) และการสร้างฮีสโทแกรมภาพ เพื่อวิเคราะห์การกระจายของสีในภาพ

- Video: [NextGenAI-2025 | OpenCV #1](https://www.youtube.com/watch?v=UeDqQ6aATm4)
- Code: [NextGen_AI_Camp_OpenCV-1.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%234/OpenCV%231/NextGen_AI_Camp_OpenCV-1.ipynb)
- Slide: [NextGen_AI_Camp_OpenCV.pdf](https://raw.githubusercontent.com/NextGen-AI-Camp/curriculum-2025/main/Week%234/OpenCV%231/NextGen_AI_Camp_OpenCV.pdf)

### OpenCV #2
ในหัวข้อนี้ จะได้เรียนรู้เพิ่มเติมเกี่ยวกับการใช้งาน OpenCV สำหรับการประมวลผลภาพและวิดีโอ เริ่มต้นด้วยการสร้าง อ่าน และเขียนไฟล์วิดีโอ ซึ่งจะทำให้เข้าใจการจัดการกับวิดีโอไฟล์ด้วย OpenCV นอกจากนี้ จะได้เรียนรู้วิธีการเพิ่ม Noise ในภาพเพื่อจำลองสัญญาณรบกวนต่าง ๆ และการกรองสัญญาณรบกวนในภาพ (Noise Removal) เพื่อให้ได้ภาพที่ชัดเจนขึ้น สุดท้าย จะได้เรียนรู้การตรวจจับเส้นขอบ (Edge Detection) ซึ่งเป็นเทคนิคสำคัญในการประมวลผลภาพสำหรับการตรวจจับและวิเคราะห์วัตถุต่าง ๆ ในภาพ

- Video: [NextGenAI-2025 | OpenCV #2](https://youtu.be/8uXuPb1oI2E)
- Code: [NextGen_AI_Camp_OpenCV-2.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%234/OpenCV%232/NextGen_AI_Camp_OpenCV-2.ipynb)

### Applying Neural Networks to Tabular Data
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับการใช้ Artificial Neural Network (ANN) ด้วย PyTorch ในการวิเคราะห์และทำนายคุณภาพไวน์จาก tabular data โดยครอบคลุมการเตรียมข้อมูล (scaling, แปลงเป็น tensor), การจัดการข้อมูลด้วย Pandas, การเลือกฟีเจอร์สำคัญ, การสร้างและฝึกโมเดล ANN ทั้งแบบ 1 ชั้นและ 2 ชั้น, การตั้งค่า hyperparameters, และการประเมินผลด้วย R² score และ accuracy

- Video: [NextGenAI-2025 | Applying Neural Networks to Tabular Data](https://youtu.be/XNeQb8BeWHQ?si=jFxhM7tv_mZt8qyZ)
- Code: [NextGen_AI_Camp_Practical_Neural_Networks.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%234/ANNs/NextGen_AI_Camp_Practical_Neural_Networks.ipynb)<br>
        [NextGen_AI_Camp_Tabular_Data_Processing_with_ANNs.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%234/ANNs/NextGen_AI_Camp_Tabular_Data_Processing_with_ANNs.ipynb)
---
## Week 5:

### CNN #1
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับ Convolutional Neural Networks (CNNs) ซึ่งเป็นโครงข่ายประสาทเทียมที่มีประสิทธิภาพสูงในการประมวลผลภาพ เริ่มจากการทำความเข้าใจ filter mask หรือ kernel และการดำเนินการคอนโวลูชัน (Convolution Operation) ในมิติที่แตกต่างกัน (1D, 2D, Multi-dimension) นอกจากนี้ จะได้เรียนรู้เกี่ยวกับ Convolution Stride, การจัดการปัญหาขอบเขต (Boundary problem) ด้วย Padding และประเภทของ Mask ทั้ง Fixed mask และ Adaptive Mask จะได้ศึกษาโครงสร้างพื้นฐานของ CNN Node ทั้ง conv และ activation รวมถึง Statistical nodes เช่น Max pooling และ Average pooling การปรับพารามิเตอร์ด้วย CNN backpropagation และ MLP layers จะได้เรียนรู้เกี่ยวกับโครงสร้างของ Simple CNN เช่น LeNet และการนำเสนอภาพผลตอบสนองตัวกรอง (Feature map) เพื่อวิเคราะห์การตอบสนองโครงข่าย นอกจากนี้ จะได้เรียนรู้วิธีการคำนวนขนาดโมเดล (จำนวนพารามิเตอร์และหน่วยความจำที่จำเป็นต้องใช้) และเทคนิคการลดขนาดโมเดลเพื่อเพิ่มประสิทธิภาพการประมวลผล
- Video: [NextGenAI-2025 | CNN #1 (EP.1/3)](https://youtu.be/SprTTU4XI-o)<br>
        [NextGenAI-2025 | CNN #1 (EP.2/3)](https://youtu.be/2DNcu4ytgqk)<br>
        [NextGenAI-2025 | CNN #1 (EP.3/3)](https://youtu.be/4doFWWNHxnA?si=jQggyhEOQ531JTeX)<br>
        [NextGenAI-2025 | CNN Backpropagation](https://youtu.be/N_Rq9i5r0mo)<br>
- Code: [NextGen_AI_Camp_CNN#1_SimpleCNN.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%235/CNN%231/NextGenAI_Camp_CNN%231_SimpleCNN.ipynb)

### CNN #2
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับการสร้างและฝึก Convolutional Neural Networks (CNNs) ด้วย Pytorch เริ่มจากการเตรียมข้อมูลและแบ่งข้อมูลเพื่อโหลดเข้าโมเดล การสร้างโมเดลโดยใช้ Pytorch รวมถึงเทคนิคการฝึกโมเดลแบบต่างๆ การปรับพารามิเตอร์ด้วย CNN backpropagation และการใช้ Loss function ในการฝึกโมเดล นอกจากนี้ จะได้เรียนรู้วิธีการวัดประสิทธิภาพของโมเดลด้วยวิธีต่างๆ เช่น Confusion Matrix เพื่อประเมินและปรับปรุงโมเดลให้มีประสิทธิภาพสูงสุด
- Video: [NextGenAI-2025 | CNN #2 (EP.1/3)](https://youtu.be/hGEPb3euxCY)<br>
        [NextGenAI-2025 | CNN #2 (EP.2/3)](https://youtu.be/UAnt2zDawOU)<br>
        [NextGenAI-2025 | CNN #2 (EP.3/3)](https://youtu.be/2DnNq9R4fx4)<br>
- Code: [NextGen_AI_Camp_LeNet.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%235/CNN%232/NextGen_AI_Camp_LeNet.ipynb)
- Train Dataset สำหรับ exercise ท้าย `NextGen_AI_Camp_LeNet.ipynb`: [train_set.zip](https://github.com/NextGen-AI-Camp/curriculum-2025/releases/download/CNN2-Exercise-Dataset/train_set.zip)
- Test Dataset สำหรับ exercise ท้าย `NextGen_AI_Camp_LeNet.ipynb`: [test_set.zip](https://github.com/NextGen-AI-Camp/curriculum-2025/releases/download/CNN2-Exercise-Dataset/test_set.zip)<br>
ในการสร้างไฟล์ผลลัพธ์การทำนายของโมเดลให้อ้างอิงรูปแบบตาม [sample_submission.csv](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%235/CNN%232/sample_submission.csv)

### TorchVision
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับเทคนิคการทำ Data Augmentation ซึ่งเป็นกระบวนการเพิ่มข้อมูลในการฝึกโมเดลโดยการปรับแต่งภาพที่มีอยู่เพื่อเพิ่มความหลากหลายของข้อมูล การเพิ่มสัญญาณรบกวนในภาพเพื่อจำลองความไม่สมบูรณ์ของข้อมูล การใช้ Gaussian Blur เพื่อเพิ่มความเบลอในภาพ การปรับแต่งภาพและมุมมองภาพ (Perspective Adjust) เพื่อจำลองการถ่ายภาพจากมุมมองต่าง ๆ การปรับแต่งการเพี้ยนสี (Color jitter) เพื่อจำลองการเปลี่ยนแปลงของสีที่อาจเกิดขึ้นในสภาพแสงต่าง ๆ และการปรับภาพกลับเฉดสี (Inverted Image) เพื่อเพิ่มความหลากหลายในการแสดงผลของภาพ ซึ่งจะช่วยให้โมเดลสามารถเรียนรู้และปรับตัวกับข้อมูลที่มีความหลากหลายมากขึ้น
- Video: [NextGenAI-2025 | TorchVision](https://youtu.be/2WCNESDUfPY)
- Code: [NextGen_AI_Camp_TorchVision.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%235/TorchVision/NextGen_AI_Camp_TorchVision.ipynb)

### Transfer Learning
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับการใช้เทคนิค Transfer Learning เพื่อปรับใช้ความรู้จากโมเดลที่ได้รับการฝึกมาแล้ว (pretrained model) กับแอพพลิเคชันใหม่ๆ โดยเริ่มจากการเลือก pretrained model ที่เหมาะสมกับงานที่ต้องการทำ และการตัดต่อเพิ่ม layer ให้โมเดลมีความเหมาะสมกับการใช้งานที่เฉพาะเจาะจง จะได้เรียนรู้การเตรียมข้อมูลและการแบ่งข้อมูลเพื่อโหลดเข้าโมเดล การสร้างโมเดลโดยใช้ Pytorch รวมถึงเทคนิคการฝึกโมเดลแบบต่างๆ ที่ช่วยให้โมเดลสามารถเรียนรู้และปรับตัวกับข้อมูลใหม่ได้อย่างมีประสิทธิภาพ
- Video: [NextGenAI-2025 | CNN Transfer Learning (EP.1/2)](https://youtu.be/eG7H6KbXjtY)<br>
[NextGenAI-2025 | CNN Transfer Learning (EP.2/2)](https://youtu.be/Lvnq0TbEdgw)<br>
- Code: [NextGen_AI_Camp_TransferLearning_Exercise.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%235/Transfer_Learning/NextGen_AI_Camp_TransferLearning_Exercise.ipynb)
        [sample_submission.csv](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%235/Transfer_Learning/sample_submission.csv)
- Data: [data.zip ](https://github.com/NextGen-AI-Camp/curriculum-2025/releases/download/Transfer-Learning-Exercise-Dataset/data.zip), [test.zip](https://github.com/NextGen-AI-Camp/curriculum-2025/releases/download/Transfer-Learning-Exercise-Dataset/test.zip)

---
## Week 6:
### การระบุตัวผู้พูดโดยใช้ระดับเสียงและ MFCC
ในหัวข้อนี้ จะได้เรียนรู้พื้นฐานการระบุตัวผู้พูด (Speaker Identification) ซึ่งเน้นการนำคุณลักษณะเฉพาะของเสียงพูดมาใช้ในการแยกแยะผู้พูดแต่ละคน โดยจะทำความเข้าใจกระบวนการประมวลผลเสียงเบื้องต้น (audio processing) เช่น A/D audio และ Fast Fourier Transform (FFT) เพื่อสกัดคุณลักษณะสำคัญอย่างระดับเสียง (pitch) และ Mel-Frequency Cepstral Coefficients (MFCC process) รวมถึงเทคนิค Voice Activity Detection (VAD) เพื่อช่วยในการคัดแยกเสียงพูด ก่อนนำคุณลักษณะเหล่านี้ไปใช้ในระบบ Speaker Identification เพื่อระบุว่าใครคือผู้พูดได้อย่างถูกต้อง
- Video: [NextGenAI-2025 | Speaker Identification using Pitch and MFCC](https://youtu.be/qZKhsJIhMdk)

### การจำแนกเสียงด้วย Convolutional Neural Networks
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับพื้นฐานการจำแนกเสียง (Audio Classification) ด้วย Convolutional Neural Networks (CNNs) โดยใช้ภาพ Spectrogram ที่แปลงจากเสียงเป็นข้อมูลนำเข้าหลัก CNNs จะเรียนรู้ลวดลายจากภาพเหล่านี้ กระบวนการนี้รวมถึงการเตรียมข้อมูล การแบ่งชุดข้อมูลสำหรับการฝึก ตรวจสอบ และทดสอบ รวมถึงรอบการฝึก (Training Loop) ที่ประกอบด้วยการส่งข้อมูล การคำนวณค่าความผิดพลาด (Loss) การปรับปรุงพารามิเตอร์ด้วย Backpropagation และการทำงานของ Activation Function นอกจากนี้ยังกล่าวถึงการวัดประสิทธิภาพด้วย Accuracy และ Confusion Matrix ตลอดจนแนวทางการทดสอบโมเดลบนข้อมูลใหม่และการปรับแต่งโมเดลที่ฝึกแล้ว
- Video: [NextGenAI-2025 | Audio Classification](https://youtu.be/B_-we37Gc70)
- Code: [NextGenAICamp_Audio Classification (การจำแนกเสียง) ด้วย CNNs.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%236/AudioClassification/NextGenAICamp_Audio%20Classification%20(%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%88%E0%B8%B3%E0%B9%81%E0%B8%99%E0%B8%81%E0%B9%80%E0%B8%AA%E0%B8%B5%E0%B8%A2%E0%B8%87)%20%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2%20CNNs.ipynb)

### Bonus
- Code : [BONUS](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%236/Bonus/NextGenAICamp_KeywordsSpotting.ipynb)

---
## Week 7:
### Effective Deep Network Architecture
ในหัวข้อนี้ จะได้เรียนรู้เกี่ยวกับการปรับปรุงประสิทธิภาพโมเดล Deep Learning อาศัยเทคนิคทางสถาปัตยกรรมที่สำคัญ โดยเฉพาะในโมเดลอย่าง Inception, GoogleNet และ ResNet ซึ่งมีการนำ skip connection และ bottleneck มาใช้ Inception Modules ช่วยให้เครือข่ายสามารถเรียนรู้คุณสมบัติได้หลายขนาดพร้อมกัน ลดความซับซ้อนในการคำนวณ ในขณะที่ ResNet ใช้ skip connection (หรือ residual connection) เพื่อแก้ปัญหา vanishing gradient ทำให้สามารถสร้างเครือข่ายที่ลึกขึ้นได้ และเพิ่มประสิทธิภาพการไหลของข้อมูล ส่วน bottleneck design ซึ่งใช้การบีบอัดและขยายมิติข้อมูลด้วย 1x1 convolution ช่วยลดจำนวนพารามิเตอร์และการคำนวณได้อย่างมีนัยสำคัญ การผสานรวมเทคนิคเหล่านี้เข้าด้วยกันถือเป็นหัวใจสำคัญของ เทคนิคการปรับปรุงประสิทธิภาพโมเดล
- Video: [NextGenAI-2025 | Effective Deep Network Architecture](https://youtu.be/RPnygkz99Co)
- Code: [NextGenAICamp_Effective_Deep_Network_Architecture_Design.ipynb](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/Week%237/Effective_Deep_Network_Architecture_Design/NextGenAICamp_Effective_Deep_Network_Architecture_Design.ipynb)
---
## Workshop:
### Workshop การประเมินราคาเสื้อผ้ามือสอง
เวิร์กชอปนี้มุ่งเน้นไปที่การประเมินราคาเสื้อผ้ามือสอง โดยน้องๆ จะได้ออกแบบโมเดลเพื่อแก้ไขปัญหาใน 2 สัปดาห์ ข้อมูลสำหรับสัปดาห์แรกประกอบด้วยรูปภาพและเสียง ซึ่งน้อง ๆ สามารถนำไปใช้ทำนายคุณสมบัติต่าง ๆ เช่น ประเภท, สี, สภาพ, กลิ่น, และการเป็นขุย ข้อมูลที่โมเดลของน้อง ๆ ทำนายได้นี้จะถูกนำไปใช้ต่อในเวิร์กชอปสัปดาห์ที่ 2 เพื่อประเมินราคาเสื้อผ้ามือสอง

#### Workshop Week 1: การจำแนกประเภท (Classification Model)
- กำหนดการ: 16 – 22 มิถุนายน พ.ศ.2568
- วัตถุประสงค์: ออกแบบโมเดลเพื่อประเมินคุณสมบัติของเสื้อผ้ามือสองจากข้อมูลรูปภาพและเสียง
- File: [NextGenAICamp_Workshop_Week1.pdf](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/WorkshopWeek%231/NextGenAICamp_Workshop_Week1.pdf)
- Data: [dataset.zip](https://github.com/NextGen-AI-Camp/curriculum-2025/releases/download/Workshop-Week1-Dataset/dataset.zip)

#### Workshop Week 2: การประเมินราคา (Regression Model) 
- กำหนดการ: 23 - 29 มิถุนายน พ.ศ.2568
- วัตถุประสงค์: ออกแบบโมเดลเพื่อประเมินราคาเสื้อผ้ามือสอง (Regression Model)
- File: [NextGenAICamp_Workshop_Week2.pdf](https://github.com/NextGen-AI-Camp/curriculum-2025/blob/main/WorkshopWeek%232/NextGenAICamp_Workshop_Week2.pdf)
- Data: [dataset.zip](https://github.com/NextGen-AI-Camp/curriculum-2025/releases/download/Workshop-Week2-Dataset/dataset.zip)