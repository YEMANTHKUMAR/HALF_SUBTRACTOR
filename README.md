# HALF_SUBTRACTOR
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/d0d5980a-6bcf-4ede-a54e-6aae3fb5f5f2)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/df70da69-5a12-4a0d-ab84-a98dad3f7e70)
![image](https://github.com/RESMIRNAIR/HALF_SUBTRACTOR/assets/154305926/2f2d6a4d-9eda-4165-8579-1d7490b5fe97)
![image](https://github.com/YEMANTHKUMAR/HALF_SUBTRACTOR/assets/160569469/6b2de9cd-0ecf-470f-be03-34fba7724ef3)
VERILOG CODE
``````
module halfsubractor(a,b,borrow,diff);
input a,b;
output borrow,diff;
xor g1(diff,a,b);
and g2(borrow,~a,b);
endmodule
``````````````
OUTPUT
![Uploading image.png…]()
