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
