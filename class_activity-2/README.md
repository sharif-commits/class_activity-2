# class_activity-2
def is_narc(n):
    """Check if a number is narc."""
    num_str = str(n) #assign not equal
    num_digits = len(num_str) #num_digits 
    sum_of_powers = sum(int(digit) ** num_digits for digit in num_str) #converted to digit  syntax error ** for exponents
    
    return sum_of_powers == n

def print_narcis_numbers(start, end):#colon error
    """Print all narc numbers in a given range."""
    for num in range(start, end + 1): #colon error comma error
        if is_narc(num): #narc name error
            print(num)

print_narcis_numbers(1000, 5000) #name error narcis
"""Submit your response here: https://forms.office.com/Pages/ResponsePage.aspx?id=vDsaA3zPK06W7IZ1VVQKHFzW4INMf2JMjyL9qPnlPbNUMFU2TjI1WjQyUlczSFNIOFBEWkxTQ0lFQS4u """