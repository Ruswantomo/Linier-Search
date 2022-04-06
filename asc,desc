# Login Program
Data_Login = {"Nama" : " ", "Password" : "123"}

while True:
    print("===>>>======>>><<<======<<<===")
    Username = input("Masukan Nama Anda : ")
    Password = input("Masukan Password Anda : ")
    print("============>>><<<============")
    print (" >>> Selamat Datang",Username," <<<\n")

#Fungsi Untuk Melakukan Algoritma Linier Search
    def linear_Search(Data, Search):

        Index = len(Data)
        Value = False
        List = []

        for i in range(0, Index):
            if Search == Data[i]:
                Value = True
                List.append(i)

        if Value == True:
            for i in List:
                print("Angka Yang Dicari Ada Pada Index : ", i)
        else:
            print("Data Yang Ingin Dicari Tidak Ditemukan !! ")

# Opsi/Pilihan Pada Menu Program
    while True:
        print("=======>>>==<>==<<<=======")
        print("| >>>> Menu Program <<<< |")
        print("==========================")
        print("|  1. Input Data         |")
        print("|  2. Method Ascending   |")
        print("|  3. Method Descending  |")
        print("|  4. Exit               |")
        print("=======>>>==<>==<<<=======")

        Opsi = int(input("Pilih Menu Program : "))
        if Opsi == 1:
            list = []
            size = int(input("Masukan Jumlah Data Yang Ingin Di Input : "))
            for i in range(size):
                x = int(input("Masukan Index {} Pada Angka : ".format(i+0)))
                list.append(x)

        elif Opsi == 2:
            list.sort()
            print(list)
            Search = int(input("Pilih Angka Yang Ingin Dicari : "))
            linear_Search(list, Search)

        elif Opsi == 3:
            list.sort(reverse=True)
            print(list)
            Search = int(input("Pilih Angka Yang Ingin Dicari : "))
            linear_Search(list, Search)

        elif Opsi == 4:
            Terus = input('Apakah Anda Ingin Keluar Dari Program ?\n(y/n) ? ')
            if Terus == 'y':
                list = []
                print(" >>> See You Next Time :) <<< ")
                exit()
