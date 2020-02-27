#今有鸡兔同笼，有三十五头，有九十四脚，问鸡兔各有几何？
for k in range(0,36):
    for r in range(0,36):
        if 2*k+4*r == 94 and k+r==35:
            print(k,r)
