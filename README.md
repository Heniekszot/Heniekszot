wysokość  = int(input("podaj wysokość [cm]:") )
masa = int( input("podaj masę ciała [kg]:") )
wiek = int( input("podaj swój wiek:") )
wysokość /=100
wysokośćDoKwadratu = wysokość * wysokość
BMI = masa / wysokośćDoKwadratu
print( f"BMI: {BMI:.2f}")
BMInew = 1,3 * BMI
print( f"BMInew: {BMInew:.2f}")

if BMI < 16 :
    print("wygłodzenie")
elif BMI < 17 :
  print("wychudzenie")
elif BMI < 18.5 :
  print("niedowaga")
elif BMI < 25 :
  print("pożądana masa ciała")
elif BMI < 30 :
  print("nadwaga")  
elif BMI < 35 :
  print("otyłość I stopnia")
elif BMI < 40 :
  print("otyłość II stopnia")
else:
  print("otyłość III stopnia")
if wiek < 25 :
  print ( "odpowiednie BMI dla Twojego wieku wynosi 19-24")
elif wiek < 35 :
  print ( "odpowiednie BMI dla Twojego wieku wynosi 20-25")
elif wiek < 45 :
  print ( "odpowiednie BMI dla Twojego wieku wynosi 21-26")
elif wiek < 55 :
  print ( "odpowiednie BMI dla Twojego wieku wynosi 22-27")
elif wiek < 65 :
  print ( "odpowiednie BMI dla Twojego wieku wynosi 23-28")
else :
  print ( "odpowiednie BMI dla Twojego wieku wynosi 24-29")
