# lesser_of_two_evens2
LESSER OF TWO EVENS: Write a function that returns the lesser of two given numbers if both numbers are even, but returns the greater if one or both numbers are odd¶
number_input = [4,4]
def lesser_of_two_evens(number_input):
    for n in number_input:
        if number_input[0]%2==0 and number_input[1]%2==0:
                if number_input[0]<number_input[1]:
                    print(number_input[0])
                else:
                    print(number_input[1])
        elif (number_input[0]%2==1 and number_input[1]%2==0) or (number_input[0]%2==0 and number_input[1]%2==1) or (number_input[0]%2==1 and number_input[1]%2==1):
                    if number_input[0]>number_input[1]:
                        print(number_input[0])
                    else:
                        print(number_input[1])
            
