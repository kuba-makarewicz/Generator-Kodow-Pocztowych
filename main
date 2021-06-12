def generator(kod1, kod2):
    kod_temp = []
    kod_final = []
    #Usuniecie ze zmiennej kod1 "-" oraz zmienienie typu na int
    kod1 = kod1.split("-")
    kod1 = int(kod1[0] + kod1[1])
    #Usuniecie ze zmiennej kod2 "-" oraz zmienienie typu na int
    kod2 = kod2.split("-")
    kod2 = int(kod2[0] + kod2[1])
    #Wyliczenie kodow pocztowych miedzy kod1 a kod2
    x = range(kod1,kod2)
    for i in x:
        j = i
        kod_temp.append(j)
    #Zmiana typu zmiennych na string i utworzenie listy
    kod_temp = str(kod_temp)
    kod_temp = kod_temp.split(", ")

    l = range(len(kod_temp))
    #Wstawienie "-" do kodów pocztowych
    for i in l:
        temp = kod_temp[i][:2] + '-' + kod_temp[i][2:]
        kod_final.append(temp)
    print(kod_final[1:])

kod1 = "79-900"
kod2 = "80-155"
generator(kod1,kod2)
