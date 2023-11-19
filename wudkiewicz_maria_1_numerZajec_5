import pandas as pd

df_titanic = pd.read_csv("/content/train.csv")
df_titanic

def new_sex(Sex):
    if Sex == 'female':
        return "0"
    elif Sex == 'male':
        return "1"

df_titanic["Sex_New"] = df_titanic["Sex"].apply(new_sex)

df_titanic
