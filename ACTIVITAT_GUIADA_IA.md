# Activitat guiada amb IA - Lab 6

Aquest laboratori treballa pagaments amb Stripe. Cada tasca ha de tenir PR, proves en mode test i revisió crítica sobre seguretat i idempotència.

## Entrega per cada tasca

- **Descripció funcional:** què s'ha de fer i per què aporta valor al projecte.
- **Prompt utilitzat:** prompt inicial i prompts de refinament, si n'hi ha.
- **Pla generat per la IA:** pla complet o resum si l'eina no el guarda.
- **Link al PR:** URL del PR amb els commits associats. Pot estar obert o merged.
- **Joc de proves:** casos correctes, errors esperats, codis HTTP, Stripe test, captures, curl/Postman o logs de webhook.
- **Revisió crítica:** què ha fet bé la IA, què heu hagut de corregir i quines decisions són vostres.

## Tasques suggerides

1. Implementar o ajustar un endpoint de domini, com `DELETE /cars/{id}`.
2. Guardar una `Transaction` quan Stripe confirma un pagament.
3. Implementar `GET /transactions` o `POST /payment/refund`.

## Exemple de joc de proves

- Cotxe existent -> 200 o 204.
- Cotxe inexistent -> 404.
- Webhook correcte -> transacció guardada.
- Webhook repetit -> no duplica transacció.
- `payment_intent_id` invàlid -> error controlat.
