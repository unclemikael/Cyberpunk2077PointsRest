# Cyberpunk 2077 Points Reset

- Level 50
- Strength 3
- Intelligence 3
- TechnicalAbility 3
- Reflexes 3
- Cool 3
- Attribute 56

``` lua
Game.SetLevel("Level", 50)
Game.AddToInventory("Items.PerkPointsResetter",1)   --Tabula E-Rasa 天书

Game.SetAtt("Strength", 3)
Game.SetAtt("Intelligence", 3)
Game.SetAtt("TechnicalAbility", 3)
Game.SetAtt("Reflexes", 3)
Game.SetAtt("Cool", 3)

Game.GiveDevPoints("Attribute", 15+7+49-15)
```

Game.GiveDevPoints(stringType, stringVal)

``` lua
Game.GiveDevPoints("Attribute", 5) -- Gives 5 attribute points 属性点
Game.GiveDevPoints("Primary", 2) -- Gives 2 perk points 专长点
```

---

## CyberEngineTweaks

<https://github.com/yamashi/CyberEngineTweaks>
