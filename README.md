# hi, i'm saurish!
```py
class Saurish:
    def __init__(self):
        self.variables = {
            'name': 'Saurish Srivastava',
            'age': 15,
            'hobby': 'coding', 'volleyball'
            'languages': ('English', 'Spanish', 'Hindi')
        }

    def description(self):
        print('------saurish------')
        for index, value in enumerate(self.variables.values()):
            if index == 0:
                print(f'Name: {value}')
            elif index == 1:
                print(f'Age: {value}')
            elif index == 2:
                print(f'Hobby: {value}')
            elif index == 3:
                print(f'Languages: {value}')

    def social_medias(self):
        platforms = {
            'Instagram': 'saurishhh',
            'Github': 'saurishs',
            'Twitter': 'saurishhh'
            'Website':``` [`https://saurish.com`](https://saurish.com/)``` py
        }

        print('\n-----contact-----')
        for key, value in platforms.items():
            print(f'{key}: {value}')


if __name__ == '__main__':
    saurish = saurishs()
    saurish.description()
    saurish.social_medias()
```
