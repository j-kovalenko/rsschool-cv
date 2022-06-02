# Pelageia Stadnik
not-even-a-junior software developer
## Contacts
* [Instagram](https://instagram.com/jkovalenk0)
* [GitHub](https://github.com/j-kovalenko)
* [Vkontakte](https://vk.com/jjj07)
* [Discord](https://discord.com/users/799527149458948096)
* [Telegram](https://t.me/jkovalenk0)
## Skills
I know Python and have experience in these libraries:
* PyQt5 (3/5)
* PyGame (3/5)
* Flask (4/5)
* requests (2/5)
* python-telegram-bot (1/5)

Still writing some projects and learning JavaScript in RS School. 

## Code examples
**Python:**
```python
def caesar_cipher(word, shift=3):
    result = ''
    for i in range(0, len(word)):
        if ord('А') <= ord(word[i]) <= ord('Я'):
            char = ((ord(word[i]) + shift - ord('А')) % 32) + ord('А')
            result += chr(char)
        elif ord('а') <= ord(word[i]) <= ord('я'):
            char = ((ord(word[i]) + shift - ord('а')) % 32) + ord('а')
            result += chr(char)
        else:
            result += word[i]
    return result
```
**JavaScript:**
```javascript
function caesar_cipher(word, shift=3) {
    let result = "";
    for (let i = 0; i < word.length; i++){
        if ('A'.charCodeAt(0) <= word[i].charCodeAt(0) && word[i].charCodeAt(0) <= 'Z'.charCodeAt(0)) {
            let char = ((word[i].charCodeAt(0) + shift - 'A'.charCodeAt(0)) % 26) + 'A'.charCodeAt(0)
            result = result + String.fromCharCode(char);
        }
        else if ('a'.charCodeAt(0) <= word[i].charCodeAt(0) && word[i].charCodeAt(0) <= 'z'.charCodeAt(0)) {
            let char = ((word[i].charCodeAt(0) + shift - 'a'.charCodeAt(0)) % 26) + 'a'.charCodeAt(0)
            result = result + String.fromCharCode(char);
        }
        else {
            result = result + word[i];
        }
    }
    return result
}
```

## Work experience
I have a few study projects:
* [basic-shop](https://github.com/j-kovalenko/basic-shop)
    - Written on python, flask. Used sqlalchemy, deployed on heroku.
    - [Deployed](https://basite.herokuapp.com/)
* [speedtest](https://github.com/j-kovalenko/speedtest)
    - Written on python, PyQt5.
* [coffee-game](https://github.com/j-kovalenko/coffee-game)
   - Written on python, PyGame.
## Education
I have just finished Yandex Lyceum: two-year course for schoolers. I've learnt Python there. You can find my certificate [here](https://lyceum.yandex.ru/certificate/check/?certNumber=220243973&lastName=%D0%A1%D1%82%D0%B0%D0%B4%D0%BD%D0%B8%D0%BA).

I have completed lower secondary school education.

## Language background
I have passed OGE(russian exam after 9th grade) of english with a grade point 5. It means, that I have at least A2-B1 level.

I also have been studying Chinese and have about A1 level.