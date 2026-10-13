# Happy Birthday, Mctominay

A one-page birthday party for Mctominay. Open the gift, bring in the squad, blow out the cake, send a wish up with the lanterns, then unlock a secret with his birthday.

The friends on stage are Viraj, Nancy, Alaric, Fluffy, and Kashie. Mctominay is the one with the cake. Their pictures are in `public/characters`.

## Run it

```bash
npm install
npm run dev
```

Then open http://127.0.0.1:4179

## Birthday date

Mctominay’s birthday is **13 October 2007**. The secret code is `1310` (day, then month). Those values live at the top of the script in `index.html`:

```js
const BDAY_MONTH = 9; // months start at 0, so 9 = October
const BDAY_DAY = 13;
const BIRTH_YEAR = 2007;
const SECRET_CODE = "1310";
```
