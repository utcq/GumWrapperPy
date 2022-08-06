# GumWrapperPy


Python Wrapper for Gum tool


# TODO

- [x] Choose
- [x] Confirm
- [x] filter
- [x] format
- [x] input
- [x] spin
- [x] write


- [ ] Python library installable via PIP
- [ ] Style Support





# Code

```python
options = [
  "Python",
  "Rust",
  "JavaScript",
  "C++"
]

# Single selection Mode
string = wrapper.choose(options)

#Multi Selection Mode
array = wrapper.choose(options, False)


```

```python


text = wrapper.input()   
username = wrapper.input("username")

#Password Mode
password = wrapper.input("password", True)   


```


```python


text = wrapper.write()
text = wrapper.write("Text Here")

```

```python

boolean = wrapper.confirm("Question")

```


```python
wrapper.spin("sleep 2")
wrapper.spin("sleep 2", "Spinning...")
wrapper.spin("sleep 2", "Spinning...", wrapper.symbols.points)


#Symbols
""" 
- line
- dot
- minidot
- jump 
- pulse
- points
- globe 
- moon
- monkey
- meter
- hamburger
"""
```


```python
wrapper.format("I :heart: Python", wrapper.formattation.emoji)

#Formattation
"""
- markdown
- code
- template 
- emoji
"""
```

