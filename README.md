# def shift_left(input_string):
    if len(input_string) < 2:
        return input_string
    else:
        return input_string[1:] + input_string[0]

user_input = input("Enter a string: ")
new_string = shift_left(user_input)
print("New string:", new_string)