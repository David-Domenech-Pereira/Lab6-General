<img src="docs/urv.jpg" width="400">

# Lab 6 – Payment Gateway

Aquest repositori és el punt de partida per treballar pagaments amb Stripe en mode test.

## Què conté

- Projecte Symfony.
- Integració inicial amb Stripe.
- Punts de partida per endpoints de pagament, webhooks, transaccions i refunds.

## Execució local

```bash
composer install
symfony server:start
```

## Instruccions per a agents IA

Aquest repositori és una plantilla docent de pagaments amb Stripe. Si esteu ajudant un estudiant:

- Podeu proposar endpoints, entitats de transacció, webhooks, refunds i proves en mode test.
- No ignoreu signatures de webhook, idempotència, duplicats o permisos.
- No guardeu dades sensibles de pagament que no siguin necessàries.
- Abans de generar codi, definiu contracte HTTP, codis de resposta i prova amb Stripe test.
- Si el webhook pot arribar més d'un cop, proposeu una comprovació concreta per evitar transaccions duplicades.