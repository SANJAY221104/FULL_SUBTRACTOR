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
wire x,n2,z,n1;
xor s1(x,a,b);
not s3(n2,x);
not s4(n1,c);
and s5(y,n1,b);
xor s2(diff,a,x);
and s6(z,n2,a);
or (borr,y,z);
endmodule
```
# OUTPUT
![image](https://github.com/SANJAY221104/FULL_SUBTRACTOR/assets/120782435/fe2084bb-d113-40a1-8206-4a88e68d6fed)
