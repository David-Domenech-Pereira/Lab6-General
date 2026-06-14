# Activitat guiada amb IA - Lab 6

Aquest repositori és el punt de partida per ampliar un flux de pagament amb Stripe. Amb pagaments, un bon prompt ha de demanar seguretat, validació, idempotència i proves en mode test.

## Què heu de fer

1. Feu un prompt per entendre el flux complet de pagament i webhook.
2. Feu un prompt per dissenyar `DELETE /cars/{id}` amb codis HTTP.
3. Feu un prompt per crear i persistir una entitat `Transaction`.
4. Feu un prompt per evitar duplicats si Stripe reenvia el webhook.
5. Feu un prompt per definir `GET /transactions`.
6. Feu un prompt per plantejar `POST /payment/refund` amb `payment_intent_id`.

## INPUTS per Moodle

- Prompt del flux Stripe en mode test.
- Prompt de `DELETE /cars/{id}` i codis HTTP.
- Prompt de `Transaction` amb camps i tipus de dades.
- Prompt d'idempotència del webhook.
- Contracte de `GET /transactions`.
- Contracte de refund i prova planificada.
- Reflexió final sobre respostes de la IA que no s'han d'acceptar sense revisar.

## Recordatori

No accepteu una resposta que ignori signatures de webhook, duplicats, permisos o proves en mode test.
