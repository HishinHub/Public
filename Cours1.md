
Voilà un programme simple en Python qui démontre la structure de base d'un programme et l'instruction if. C'est un exemple concret et fonctionnel que tu peux copier-coller pour tester immédiatement.

## EXEMPLE 1 : Programme simple - Vérifier l'âge (À tester d'abord)

**Voilà un programme simple en Python qui démontre la structure de base d'un programme et l'instruction `if`. C'est un exemple concret et fonctionnel que tu peux copier-coller pour tester immédiatement.**

```python
age_texte = input("Quel âge as-tu ? ")
print("Tu as tapé :", age_texte)
age = int(age_texte)  
print("Convertit en nombre :", age)
if age >= 18:
    print("✅ Tu es majeur.")
else:
    print("❌ Tu es mineur.")
print("Merci d'avoir participé !")
```

## Explications détaillées

**Ce programme fait exactement 4 choses dans l'ordre** :

1. **`input("Quel âge as-tu ? ")`** → Demande l'âge et stocke la réponse dans `age_texte` (c'est **TOUJOURS une chaîne de caractères** `"25"`)

2. **`int(age_texte)`** → Convertit `"25"` en nombre entier `25` et le stocke dans `age`

3. **`if age >= 18:`** → Teste si l'âge est supérieur ou égal à 18
   - Si vrai → exécute la ligne indentée `print("✅ Tu es majeur.")`
   - Si faux → exécute `else:` puis `print("❌ Tu es mineur.")`

4. **`print("Merci d'avoir participé !")`** → S'exécute **toujours** (en dehors du `if`)

**Règles Python importantes** :
- `:` obligatoire après `if` et `else`
- **4 espaces** d'indentation sous `if` et `else`
- Le programme s'exécute **ligne par ligne d'en haut en bas**

**Teste avec** : 15 → mineur, 20 → majeur, 18 → majeur

***

## EXERCICE 2 À RÉALISER

**Objectif** : Adapter ce programme pour comparer **deux nombres**.

**À faire** :
1. Demander `Premier nombre :` et `Deuxième nombre :`
2. Afficher exactement :
   ```
   Le premier nombre est le plus grand.
   Le deuxième nombre est le plus grand.
   Les deux nombres sont égaux.
   ```

**À toi de jouer !** Copie le code ci-dessus et modifie-le. 🚀

