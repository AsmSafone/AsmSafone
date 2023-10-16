# <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> Hi, I'm Safone | [![Profile Views](https://komarev.com/ghpvc/?username=AsmSafone&style=for-the-badge)](https://github.com/AsmSafone)

<p align="center">
  <a href="https://t.me/AsmSafone"><img src="https://user-images.githubusercontent.com/77770753/117139498-f081c400-adc9-11eb-9aaf-f895a54ecc67.gif"></a>
    </p>
<p align="center">
    <img
        width="49%"
        src="https://github-readme-stats.vercel.app/api?username=AsmSafone&count_private=true&include_all_commits=true&show_icons=true&theme=tokyonight&custom_title=GitHub+Stats"
    />
    <img
        width="49%"
        src="https://github-readme-streak-stats.herokuapp.com?user=AsmSafone&theme=tokyonight"
    />
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
print("Hola! Welcome To Safone's World !! 😎")
​

```
</h3>

[![An image of @asmsafone's Holopin badges, which is a link to view their full Holopin profile](https://holopin.me/asmsafone)](https://holopin.io/@asmsafone)
