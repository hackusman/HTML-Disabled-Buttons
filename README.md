# Résolution du Challenge

Pour résoudre ce challenge, voici une méthode simple que vous pouvez suivre :

## Étape 1 : Inspecter la Page

1. **Ouvrir les outils de développement :** Appuyez sur la touche `F12` ou faites un clic droit sur la page web et choisissez `Inspecter` pour ouvrir les outils de développement de votre navigateur.

## Étape 2 : Modifier l'Attribut `disabled`

2. **Localiser l'élément de formulaire :** Dans les outils de développement, trouvez la balise `<form>` contenant l'élément `<input>` qui est désactivé.

3. **Modifier l'attribut `disabled` :**
   - Cherchez l'élément `<input>` qui a l'attribut `disabled`.
   - Effacez cet attribut. Cela peut être fait en cliquant sur l'attribut `disabled` dans l'inspecteur d'éléments et en le supprimant.

   ```html
   <input type="text" name="password" disabled>
   ```

   Devient :

   ```html
   <input type="text" name="password">
   ```

## Étape 3 : Remplir le Champ et Soumettre

4. **Saisir le texte souhaité :** Maintenant que le champ de saisie est activé, vous pouvez entrer ce que vous voulez. Par exemple, tapez `TU_PEUX`.

5. **Cliquez sur le bouton approprié :** Cliquez sur le bouton `member access` ou tout autre bouton qui soumet le formulaire.

6. **Obtenez le mot de passe :** Après avoir soumis le formulaire, le mot de passe devrait apparaître. Dans ce cas, le mot de passe est `HTMLCantStopYou`.

## Explication

En HTML, l'attribut `disabled` est utilisé pour rendre un élément de formulaire non interactif. Lorsqu'un élément est désactivé :

- L'utilisateur ne peut pas interagir avec cet élément.
- L'élément est généralement grisé pour indiquer qu'il est inactif.
- Les valeurs des éléments désactivés ne sont pas envoyées lorsque le formulaire est soumis.

En supprimant cet attribut, vous permettez à l'utilisateur d'interagir avec l'élément et de soumettre les valeurs du formulaire.

