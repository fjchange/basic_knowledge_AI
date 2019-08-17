## 1. AU-ROC (Aera under Recevier opearting characteristic)
TPR=len(TP)/len(P)
FPR=len(FP)/len(N)
ROC is the curve of TPR-FPR
AUC is the area under ROC

## 2. Precision-Recall AUC

## 3. EER (eaual error rate)
EER is the point on the ROC curve where FPR=1-TPR, which mean the crossing of ROC curve and (1-FPR)
EER is the FPR value of that point

## 4. Accuracy
## 5. EDR (equal detection rate)
EDR=1-EER
