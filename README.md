# -Write-a-program-to-Generate-Student-Result.-Required-Fields-sno-name-group-6-subjects-total-avg-gra
sno=int(input('enter sno')) sname=input('enter name') s1=int(input('s1 marks')) s2=int(input('s2 marks')) s3=int(input('s3 marks')) s4=int(input('s4 marks')) s5=int(input('s5 marks')) s6=int(input('s6 marks')) total=s1+s2+s3+s4+s5+s6 avg=total/s6 if avg>=91:     print('o-grade') elif avg>=81:         print('A-grade') elif avg>=71:             print('B-grade') elif avg>=60:                 print('C-grade') elif avg>=50:                     print('D-grade') elif avg>=40:                         print('pass') else:     print('fail')
