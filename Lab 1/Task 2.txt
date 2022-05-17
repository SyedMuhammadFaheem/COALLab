INCLUDE Irvine32.inc
.code
main PROC
mov eax, 69h
mov ebx, 420h
call DumpRegs
exit
main ENDP
END main