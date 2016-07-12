# Statistical-Lorem
Bored of weird standard looking 'Lorem Ipsum'?
Obtain theme based random paragraphs!

Statistical Lorem allows you to specifify a theme, number of paragraphs, and length of paragraph:
```python
from statlorem import ipsum
# Will generate 2 paragraphs with 60 words each.
print ipsum('scifi', 2, 60)
"""
Blessed! in smallness, in shrubberies that was it and fall to the ground, then threaten totear me to new york. he doesn't take me away." my nose was bending down, his rocket! itraverse a temple! it is weathered, leaning as far as we found it doesn't take me tothe city yonder, and as we are all get into insensibility."i am.

	Concernful sympathy, andin a world to think so, "it was the rest of course."it is taken; you learnt things you insist," he did investigate them."the receptionist is incredibly tall, ofblack foundation and a passing boat as myself andas tall. there werenothing else in the gates, and gloomy, and the things as we hate, but i've got a millionmiles below is.
"""
```

We currently only support 'scifi', and 'philosophy'.
If interest is shown I'll add more options.

## Installation

Through pip:
```sh
$ pip install statlorem
```

Cloning the repo:
```sh
$ git clone https://github.com/jesuscast/Statistical-Lorem.git
```

If you have numpy already then you can just copy the file statlorem.py into your directory if you want.

## Usage
Now import the function 'ipsum'
```python
from statlorem import ipsum

# Will generate 2 paragraphs with 60 words each.
print ipsum('scifi', 2, 60)
```