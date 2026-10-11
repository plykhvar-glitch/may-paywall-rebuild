# May — the paywall, filled with what onboarding just learned

**Live page: https://plykhvar-glitch.github.io/may-paywall-rebuild/**

May's trial paywall, gift game and −74% offer, rebuilt in May's own design and fed by what the
onboarding already asks and computes: whether she is expecting, the pregnancy start date (and the
due date May calculates from it), and whether she is in a couple. Change the answers under the phone
and the screens rewrite themselves. Flip **Today** to see the version that ships now. Spanish,
French and English, light and dark, plus a 30-second walkthrough.

## The five changes

| # | Change | Today | Now | Expected impact |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Lead with her due date | The top half of the paywall is empty | "Tu bebé llega el 26 de marzo" in May's own lilac due-date card, with her week and the 3D baby | CR +15–20% |
| 2 | Say what May does at her stage | No feature on the paywall | Four of May's own benefit rows, ordered for pregnancy, trying or parenting, plus account sharing for couples | CR +10–15% |
| 3 | Put the proof next to the price | Only "Elegido por 1560 personas hoy" | 4.8 ★, +1 millón, 98% and Berta's App Store review under the price | CR +10–15% |
| 4 | Make the −74% offer about her year | Timer, price, "Acceder a la oferta" | "Hasta octubre de 2027: el resto de tu embarazo y los primeros meses de tu bebé", and "Obtener 12 meses por 39,99 €" | CR +5–10% on the offer |
| 5 | Put a date on the free week | "7 días gratis" with no end date | "Hoy: todo May, gratis" → "18 de octubre: 59,99 € / año · Cancela antes y no pagas nada" | CR +3–8% |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for May.*

Prices, the trial, the offer, the figures and the copy come from May's own in-app screens and App
Store listings; Berta's quote is her App Store review, verbatim. Due dates are computed the way May's
onboarding computes them.

## Run locally

```bash
python3 -m http.server 8000
```
