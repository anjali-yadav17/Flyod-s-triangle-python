# Flyod-s-triangle-python
def generate_floyds_triangle(rows):
    number = 1
    for i in range(1, rows + 1):
        for j in range(1, i + 1):
            print(number, end=" ")
            number += 1
        print()

# Example: generating Floyd's Triangle with 4 rows
generate_floyds_triangle(4)
