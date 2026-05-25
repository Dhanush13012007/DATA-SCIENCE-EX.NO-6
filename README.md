# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import seaborn as sns
import pandas as pd
df=pd.read_csv("iris.csv")
df.head()

sns.jointplot(x="petal_length", y="petal_width", data=df, kind="hex")

sns.pairplot(data=df, vars=["sepal_length","sepal_width"], hue="species")

sns.displot(df["petal_length"], kde=True)

sns.countplot(y="species", data=df)

sns.boxplot(x="species", y="petal_length", data=df)

sns.barplot(x="species", y="petal_length", data=df)

sns.violinplot(x="species", y="petal_length", data=df)

```

<img width="681" height="195" alt="Screenshot 2026-05-25 215030" src="https://github.com/user-attachments/assets/ead41745-026b-4ead-ab22-b9f63b02fb22" />

<img width="726" height="635" alt="Screenshot 2026-05-25 215039" src="https://github.com/user-attachments/assets/d7bcf5e5-c0c4-47d5-af5d-2a361fa1ca7b" />

<img width="741" height="535" alt="Screenshot 2026-05-25 215049" src="https://github.com/user-attachments/assets/b386f348-0408-4e48-a69c-eae048944cea" />

<img width="730" height="538" alt="Screenshot 2026-05-25 215055" src="https://github.com/user-attachments/assets/7a66335d-fff5-43e7-94a9-7ac124487211" />

<img width="778" height="467" alt="Screenshot 2026-05-25 215103" src="https://github.com/user-attachments/assets/17ed671d-3f94-43af-a5f3-f5e1d9c434ec" />

<img width="703" height="473" alt="Screenshot 2026-05-25 215109" src="https://github.com/user-attachments/assets/6e85fdfd-ac42-4e41-9f45-a9260dda638a" />

<img width="799" height="484" alt="Screenshot 2026-05-25 215116" src="https://github.com/user-attachments/assets/6e4decbb-84a0-445c-88b1-796898539cb2" />

<img width="678" height="484" alt="Screenshot 2026-05-25 215128" src="https://github.com/user-attachments/assets/eaf9e084-9e3c-4f0e-b0f0-70f654408f1e" />

# Result:
Data Visualization using seaborn python library for the given datas has been performed successfully.

