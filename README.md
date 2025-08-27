# Kushki
# Kushki API - Flujo de Pago Completo (Sandbox)

Este repositorio demuestra cómo implementar un flujo de pago completo para **pagos únicos con tarjeta de crédito** usando la **API de Kushki** en ambiente **UAT (Sandbox)**.  
Incluye los pasos básicos del ciclo de vida de un pago:

1. **Solicitar un token de tarjeta** (`/card/v1/tokens`)
2. **Realizar un cargo (charge)** (`/card/v1/charges`)
3. **Anular la transacción (void)** (`/card/v1/void`)
4. **Consultar lista de transacciones** (`/transactions`)

Cada paso incluye el request en formato `cURL` y la respuesta obtenida.

