# Print-A-Triangle
rows = 5  # Number of rows for the triangle
for i in range(1, rows + 1):
    print(' ' * (rows - i) + '*' * (2 * i - 1))
