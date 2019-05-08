# Fruit Facts API

Enter a fruit as the url slug and see a random fruit fact displayed as json.

Example:

`localhost:5000/apple`

Response:

```
{
  "fruit": "apple",
  "fact": "There are over 10,000 varieties of apples grown around the world",
}
```

To run this code, run: `node index.js`

Fruit facts from Fruit Ninja game.

# API

/ -index page shows greeting
/help -help page shows help and available fruits
/:fruit -fruit page shows info about the given fruit
not found page shows up when search does not match available fruits

All fruits:

apple,
banana,
coconut,
kiwi,
lemon,
lime,
orange,
pear,
watermelon,
mango,
pineapple,
passion
