# 🐶 Python OOP Challenge: Build Your Own Digital Pet

Welcome to this week's Python challenge! 🎉

class AnimalCompanion:
    
def __init__(self, identifier):
    self.name = nombre
self.hunger = 50
self.energy = 50
self.happiness = 40

def eat(self, food_amount):
    self.hunger = min(100.hunger + food_amount)
self.energy = max(0, self.energy - 5)
print(f"{sself.name} ate some hunger decreased!")

def sleep(self.minutes):
    self energy = min(100. self.energy.energy + hours + 10)
    self.hunger =  max(0, self.hunger - hours * 3)
    print(f"{self.name} slept for {hours} hours. Energy restored")

def play(self, minutes):
    self.happiness = min(100, self.happiness + minutes * 0.5)
    self.energy = max(0, self.energy - minutes * 0.3)
    self.hunger = max(0, self.hunger - minutes * 0.2)
    print(f"{self.name} played for {minutes} minutes so fun")

def get_status(self):
    status = {
        'name' : self.name,
        'hunger' : self.name,
        'energy' : self.energy,
        'happiness' : self.name,
        'mood' : self._get_mood()
    }

return status
def _get_mood(self):
    if self.happiness > 70 and self.energy > 50 and self.hunger < 30:
        return "Ecstatic"
    elif self.happiness < 30 or self.energy < 20 self.hunger > 80:
        return"Grumpy"
    else:
        return "content"
