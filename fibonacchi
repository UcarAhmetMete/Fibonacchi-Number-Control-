def main():

    document = input("Enter the document:")
    # You can open both files with that way.
    try:
        with open(document, "r") as file:
            fibonacchi = []
            fibonacchi.append(0)
            fibonacchi.append(1)
            sum = 0
            for i in range(0,98):
                sum = fibonacchi[i] + fibonacchi[i+1]
                fibonacchi.append(sum)
            # print(fibonacchi)
            # I created a list that includes first 100 fibonacci number.
            print(len(fibonacchi))
            line = file.readlines()
            for i in line:
                number = i.strip().split(", ")
            print(fibonacchi)
            # WE ALSO CAN PRINT fibancci as set we can use set(fibanacci)
            for j in range(3,100):
                # print(fibonacchi[j] , "!", int(number[0]))
                # print(number[0])
                if "0" == number[0] and "1" == number[1] and "1" == number[2]:
                    print("This File Contains a subsequence of the FIBONACCO series.The program prints YES")
                    break
                if fibonacchi[j] == int(number[0]) and fibonacchi[j+1] == int(number[1]) and fibonacchi[j+2] == int(number[2]):
                    print("This File Contains a subsequence of the FIBONACCO series.The program prints YES")
                    break
                else:
                    print("This File DOES NOT Contains a subsequence of the FIBONACCO series.The program prints NO")
                    break
            # e j < 100 and fibonacchi[j] == int(number[0]) and fibonacchi[j+1] == int(number[1]) and fibonacchi[j+2] == int(number[2]):
            #     pwhilrint("YES")
            #     break
                # if fibonacchi[j] != int(number[0]) and fibonacchi[j+1] != int(number[1]) and fibonacchi[j+2] != int(number[2]):
                #     print("NO")

    except FileNotFoundError:
        print("The file you want to run is not exist !")
main()
