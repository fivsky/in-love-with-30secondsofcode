# in-love-with-30secondsofcode
My sympathy to this beautiful site is expressed in my translations of favourite pieces of text. Enjoy.

if __name__ == "__main__":
  print("Hello, World!")  /мы часто встречаем эти строчки кода...но что же они значат? Попробуем разобраться.

В жизни бывают разные ситуации. Например, оказывается, что мы можем дважды вызывать одну и ту же функцию. Например:

/script1
def do_stuff:
  print('Doing stuff')

/script2
do_stuff()
from script1 import do_stuff

do_stuff()

Вот такие мы прикольные неоптимизированные ребята. 

Как же нам избежать двойного вызова функций? Без паники, крошки. Это можно сделать просто - добавив специальную строку кода в script1:

if __name__ == "__main__" 

Что же такого делает этот метод? Проверяет, запускается ли код напрямую или же код был импортирован. 

Теперь, когда мы используем этот метод, мы вызываем функцию в script2 только один раз. 

Очень круто. 

В честь этого метода небольшое хокку, пацаны. В качестве бонус-трека дочитавшим до конца кодовую миниатюрку. 

Люблю name main в начале мая. 
  Добавлю лихо в код себе. 


R



