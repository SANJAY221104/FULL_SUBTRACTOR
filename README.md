# FULL_SUBTRACTOR
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/351addef-f7bb-4862-9817-616a41b4c882)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/906152b8-63bc-4f70-9132-6b6b4420b22d)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/7d480140-153a-4a7e-a6d2-5323c6bd4974)
# PROGRAM
```python
module full_subtractor(a,b,c,diff,borr);
input a,b,c;
output diff,borr;
wire w1,w2,w3,w4;
xor s1(w1,a,b);
not s3(w2,w1);
not s4(w4,c);
and s5(y,w4,b);
xor s2(diff,a,w1);
and s6(w3,w2,a);
or (borr,y,w3);
endmodule
```
# OUTPUT
![image](https://github.com/SANJAY221104/FULL_SUBTRACTOR/assets/120782435/fe2084bb-d113-40a1-8206-4a88e68d6fed)
