# Hey There! <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> | [![Profile views](https://gpvc.arturio.dev/AsmSafone)](https://github.com/AsmSafone)
![Safone Github stats](https://github-readme-stats.vercel.app/api?username=AsmSafone&show_icons=true&theme=tokyonight)
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
