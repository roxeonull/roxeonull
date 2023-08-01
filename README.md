```python
from github.profile import ReadMe
class roxeonull ( ReadMe ) :
    def __init__ ( self ) :
        self.username  = "roxeonull"
        self.location  = "Indonesia"
        self.discord   = "roxeonull#1628"
        self.languages = [ "PHP", "Kotlin", "Javascript", "C#", "Java" ]
    def about ( self ) :
        print( f"Hi, I'm {self.username}. Contact me at {self.discord}" )
me = roxeonull()
me.about()

