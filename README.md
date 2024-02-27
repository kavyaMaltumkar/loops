# loops
def print_positive_numbers(input_list):
    positive_numbers = [num for num in input_list if num > 0]
    print("Output:", positive_numbers)

# Input list examples
list1 = [12, -7, 5, 64, -14]
list2 = [12, 14, -95, 3]

# Call the function with input lists
print("Input:", list1)
print_positive_numbers(list1)

print("\nInput:", list2)
print_positive_numbers(list2)

 output

Input: [12, -7, 5, 64, -14]
Output: [12, 5, 64]

Input: [12, 14, -95, 3]
Output: [12, 14, 3]
