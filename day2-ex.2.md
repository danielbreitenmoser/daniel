import pandas as pd

file=open("data.pgxseg")

lines=file.readlines()

file.close()

lines=lines[1006:]

print(lines)

df=pd.DataFrame(lines)

print(df)


I have never really worked with a dataframe before so pretty much everything i did was wrong.


