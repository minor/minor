# hi, i'm saurish!
```py
class saurishsrivastava:
    def __init__(self):
        self.variables = {
            'name': 'Saurish Srivastava',
            'age': 16,
            'hobbies': 'coding', 'volleyball', 'debating', 'giving back'
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
                print(f'Hobbies: {value}')
            elif index == 3:
                print(f'Languages: {value}')

    def social_media(self):
        platforms = {
            'Instagram': 'saurishhh',
            'Github': 'saurishs',
            'Twitter': 'saurishhh'
            'Website': 'https://saurish.com'
        }
        
    def contact(self):
        platforms = {
            'Mail': 'me@saurish.com'
        }
    
if __name__ == '__main__':
    saurish = saurishsrivastava()
    saurish.description()
    saurish.social_media()
    saurish.contact()
```
