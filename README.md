### Index
**[getmyfreeweeklygame](https://github.com/qgeffard/getmyfreeweeklygame/blob/master/README.md#getmyfreeweeklygame)**</br>
**[Méthode Login](https://github.com/qgeffard/getmyfreeweeklygame/blob/master/README.md#m%C3%A9thode-login)**</br>
**[Méhode 1](https://github.com/qgeffard/getmyfreeweeklygame/blob/master/README.md#m%C3%A9hode-1)**</br>

# getmyfreeweeklygame
- Goal :
''Here you can find a script that will automatically add the free weekly epicgames to your library''

# Méthode Login
- [x] Allez sur l'url https://www.epicgames.com/id/login
- [x] Récup  `<input>` avec `id="email"`
- [x] Récup  `<input>` avec `id="password"`
- [x] Récup `<button>` avec `id="login"`
- [x] Saisir l'email dans`<input>` avec `id="email"`
- [x] Saisir le mot de pass dans `<input>` avec `id="password"`
- [x] Clic sur le `<button>` avec `id="login"`

# Méhode 1
- [x] Go to https://www.epicgames.com/store/fr

- [ ] Récupe `"span"` Gratuit maintenant

- [ ] on remonte de 3 élément parent (jusque au `<a aria-label>`)

- [ ] Dans le `<a aria-label>` on récup le contenue de `href=""`

  >  https://www.swtestacademy.com/click-links-console-xpath-jquery/ 

- [ ] Ce rendre à l'url que le`href=""` contient

- [ ] Récup le `PurchaseButton-button`

- [ ] Clic sur le `PurchaseButton-button`
