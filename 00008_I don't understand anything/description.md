We have just seen that sentences, phrases or paragraphs written in a natural language should conform to certain syntactic rules. But what happens when we write code - commands for a computer, written in a formal language? :thinking: Then we have to follow their rules too!


For example, the following code...
 
```python
def hello_world():
	print('hello world')
```

…is not the same as…

```python
Def Hello_world():
	Print('hello world')
```

…or this:

```python
def hello_world[]:
	print('hello world')
```

…nor this:

```python
def hello_world():
print('hello world')
```

If we don't adhere to these principles, which we call _syntax_, the computer cannot interpret our intent. As a result, our programs don't work as we intended :thumbsdown:

> Select which portion of code is identical to:
>
```python
def double(number):
   return number * 2
```