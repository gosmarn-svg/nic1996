.globl _start
.text


_start:
li t0,3 #valore di x
li t1,5 #valore y
beq t0,t1,ELSE
addi t0,t0,2
beq zero,zero,endif





ELSE:
addi t1,t1,-1


endif:

li a7,10
ecall
