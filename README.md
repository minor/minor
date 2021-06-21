# hey, i'm saurish
```py
class saurishsrivastava:
    def __init__(self):
        self.variables = {
            'name': 'saurish',
            'age': 16,
            'hobbies': 'coding, volleyball, debating',
            'languages': 'english, spanish, hindi'
        }
        
        self.social = {
            'instagram': '@saurishhh',
            'github': '@minor',
            'twitter': '@saurishhh',
            'contact': 'me@saurish.com',
            'website': 'saurish.com'
        }

    def description(self):
        for index, value in enumerate(self.variables.values()):
            if index == 0:
                print(f"--- hi, i'm {value} ---")
            elif index == 1:
                print(f'age: {value}')
            elif index == 2:
                print(f'hobbies: {value}')
            elif index == 3:
                print(f'languages: {value}')

    def social_media(self):
        print('\n--- social media & contact ---')
        for index, value in enumerate(self.social.values()):
            if index == 0:
                print(f'instagram: {value}')
            elif index == 1:
                print(f'github: {value}')
            elif index == 2:
                print(f'twitter: {value}')
            elif index == 3:
                print(f'contact: {value}')
            else:
                print(f'website: {value}')


if __name__ == '__main__':
    saurish = saurishsrivastava()
    saurish.description()
    saurish.social_media()
```
