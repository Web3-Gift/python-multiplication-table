# python-multiplication-table
一个简单的Python程序，用于生成九九乘法表。这个程序通过嵌套的循环来计算并打印出九九乘法表的所有结果。它可以帮助初学者学习和理解循环结构以及基本的数学运算。
def multiplication_table():
    for i in range(1, 10):
        for j in range(1, i + 1):
            print(f"{j} x {i} = {i * j}\t", end="")
        print()

multiplication_table()
