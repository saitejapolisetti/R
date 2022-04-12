# Aesthetic Points
-  X, Y
```
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g))	
```
![billLength_billDepth.jpeg](billLength_billDepth.jpeg)
- Color
```
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, color = species))
```
![[bodyMass_flipperLength_colorSpecies.jpeg]]
**If we want to change the appearance of our overall plot without regard to specific variables, we write code oustside og the aes function**
```
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g), color = 'purple')
```
![[bodyMass_flipperLength_colorPurpleAll.jpeg]]
- Shape
```
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, shape = species))

```
![[bodyMass_flipperLength_shapeSpecies.jpeg]]
- Size
```
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, size = species, shape = species, color = species))

```
![[bodyMass_flipperLength_sizeSpecies.jpeg]]
- Alpha
```
ggplot(data = penguins) + geom_point(mapping = aes(x = flipper_length_mm, y = body_mass_g, alpha = species))
 
```
![[bodyMass_flipperLength_alphaSpecies.jpeg]]




