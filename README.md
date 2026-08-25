# Cargador-Iberdrola-Benidorm-Av-Benissa

Monitor de disponibilidad del cargador Iberdrola situado en Avenida Benissa 1, Benidorm.

- Identificador interno Iberdrola (`cuprId`): `15502`
- Dos conectores Tipo 2 de 22 kW
- Aviso por Telegram cuando queda al menos un conector libre

## Configuración en GitHub

Crea estos secretos en **Settings > Secrets and variables > Actions**:

- `TELEGRAM_BOT_TOKEN`
- `TELEGRAM_CHAT_ID`

El flujo también puede ejecutarse manualmente desde la pestaña **Actions**.
