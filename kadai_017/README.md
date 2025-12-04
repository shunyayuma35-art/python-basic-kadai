# Humanクラスの定義
class Human:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def check_adult(self):
        if self.age >= 20:
            print(f"{self.name}さんは大人です。")
        else:
            print(f"{self.name}さんは大人ではありません。")

# Humanインスタンスを作成してリストに追加
humans = [
    Human("太郎", 25),
    Human("花子", 19),
    Human("次郎", 30),
    Human("美咲", 18)
]

# リストの全要素でcheck_adultメソッドを呼び出す
for person in humans:
    person.check_adult()
太郎さんは大人です。
花子さんは大人ではありません。
次郎さんは大人です。
美咲さんは大人ではありません。
