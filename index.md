# What is Markdown

Markdown is a very lightweight markup language that lets you create rich text (meaning text that has emphasis, headers, etc) in any plain text editor. **Markdown**, like HTML, allows you to specify text formatting, but it is far less expressive than HTML, which is perfectly fine since it is only meant to format text and not create full _web pages_.

The resulting Markdown you write is then fed in to a converter that replaces the Markdown syntax with HTML, which can then be **displayed** on a web page. In addition to the Markdown syntax, you can also write plain HTML as well, so if you have some more _complicated_ structure you want to add in-line with your text, you'll still have the ability to do so.

## Blockquotes in Markdown

> Of all the things I've lost
>  I miss my mind the most. - Mark Twain
>  his can get a bit **tedious** for long blocks of continuous text, so instead you can just use a single.

## Lists in Markdown
- **Tea**
- cofee
- **Milk**
- Cappucinno

### Countries in World!
1. **America**
1. Australia
1. Canada
1. **Brazil**
1. India
1. New Zealand

### Continents in World!
+ _Asia_
+ _America_
+ _Australia_
+ _South America_

## Code Blocks in Markdown

Checkout this code:

```C
def fibonacci(number):
        if number <= 1:
            return number
        else:
            return fibonacci(number - 1) + fibonacci(number - 2)

And use the function like this:

    fib_number = fibonacci(8)
    print 'The 8th Fibonacci number is:', fib_number

```
Wow, that was amazing...


## Images in Markdown

![Markdown!](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

### IOT Image

![Internet Of Thing](images\IOT-Image-1.avif "5G")

### 5G Image
![5G](images\IOT-Image2.jpg "IOT")

---

## Links in Markdown

[Stack Abuse](http://stackabuse.com "Stack Abuse Title")

---
