# java-week2-mini3

int
result
=
6 
+
12
+
19
;

MOVI R1, 6
MOVI R2, 12
ADD R0, R1, R2
MOVI R2, 19
ADD R0, R0, R2
STORE [0], R0

為什麼第二次可以覆蓋 R2:
前一次的R2已經完成運算，第二次R2就可以直接覆蓋

若輸入改成 int result=7+3+1; ，目前程式為什麼無法按預期讀
取？
它們被視為同一串完整的文字，導致後面的程式沒有資料
