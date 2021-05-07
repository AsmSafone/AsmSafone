# Hey There! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> | [![Profile views](https://gpvc.arturio.dev/AsmSafone)](https://github.com/AsmSafone)

<p align="center">
  <a href="https://t.me/AsmSafone"><img src="https://user-images.githubusercontent.com/77770753/117139498-f081c400-adc9-11eb-9aaf-f895a54ecc67.gif"></a>
    </p>
<h3>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple[str, ...] = ("Python", "Bash", "HTML", "CSS")
    misc        : tuple[str, ...] = ("Docker", "Linux", "FastAPI")
    ongoing     : tuple[str, ...] = ("Django", "Java", "JavaScript")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
printf("Thank You Very Much. Stay Tuned With Us !!"
​

```
</h3>
