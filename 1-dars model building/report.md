Model Building- bu ma'lumotlar asosida kampyuterga qununiyatlarni o'rgatib yangi ma'lumot uchun bashorat qiladigan modelni yaratish jarayoni.

Algoritm va model bir xil narsa emas.Algoritm bu amallar ketma ketligi masalan Linear Regression Algoritmi.Biz datalar orqali Algoritmni train qilamiz va naatijada model hosil bo'ladi.

Evaluation-bu modelni baxolash bosqichi model qanchalik to'g'ri ishlayotganini bilish uchun ishlatilinadi.2 turga bo'linadi classification va regression.
Classification uchun Accuracy_score va Classification Report ishlatilinadi.
Regression uchun R2-score,MSE,MAE,RMSE ishlarilinadi.

Model evaluation model yaratilgandan keyin model qanchalik to'g'ri ishlayotganini tekshirish.

Confusion matrix -bu machine learning modelining klassifikatsiya qilish natijalarini baxolash jadvali.

TP(True positive)-model 'Ha' dedi aslida ham Ha
TN(True Negative)-model 'Yoq' dedi aslida ham yoq.
FP(False Positive)-model ha dedi aslida yoq
FN(False Negative)-model yoq dedi aslida ha

Bular classification evaluationning eng muhim fundamentlaridan bir.

accuracy=(TP+TN)/TP+TN+FP+FN

Precision-Model positive deb topganlarning nechtasi haqiqatda positive.
precision=TP/TP+FP

Recall-haqiqatda positive bo'lganlarning nechtasini model topdi.

Recall=TP/TP+FN

Precision va Recall ning farqi precision aytilgan positivlar Recalkl mavjud bo'lgan positivlar.

F1 score Precision va Recallni bitta ko'rsatgichda birlashtirilgani.

F1=2*((precision*Recall)/precision+recall)

F1 ikkala qiymatning balansini hisobga oladi shuning uchun F1-score classification modelini baxolashda ishlatilinadigan mixim metric.

Classification report-classificatsiya modelini ishlash samaradorligini precision,recall,F1-score va accuracy orqali ko'rsatib beruvchi hisobot.