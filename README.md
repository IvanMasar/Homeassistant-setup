# 🏠 Inteligentná domácnosť (Maturitný projekt)

Tento projekt obsahuje kompletné riešenie inteligentnej domácnosti založené na platforme **Home Assistant** a vlastnoručne vyrobených zariadeniach s čipmi **ESP32** a **ESP8266**.

## 🛠️ Štruktúra projektu (Zariadenia)
V nasledujúcich priečinkoch nájdete všetko potrebné na zostrojenie a oživenie jednotlivých modulov (zdrojový kód, 3D modely krabičiek a fotografie):

* [**Pohybové čidlo**](./pohybove_cidlo) – Automatické rozsvecovanie svetiel a zabezpečenie.
* [**Roleta**](./roleta) – Automatizované ovládanie žalúzií/roliet.
* [**Teplomer**](./teplomer) – Monitorovanie teploty a vlhkosti v miestnosti.

---

## 📊 Nastavenie Dashboardu (Užívateľské rozhranie)
Dashboard v Home Assistantovi slúži na vizualizáciu dát a manuálne ovládanie všetkých prvkov.

### Ukážka rozhrania
![Môj Dashboard](images/dashboard_screenshot.png) 
*(Nezabudni nahrať screenshot do priečinka images a premenovať ho na dashboard_screenshot.png)*

### Ako importovať môj dashboard
Ak si chcete nastaviť rovnaký vzhľad, postupujte takto:
1. V Home Assistantovi vytvorte nový prázdny Dashboard.
2. V pravom hornom rohu kliknite na tri bodky -> **Upraviť ovládací panel**.
3. Opäť kliknite na tri bodky -> **Editor konfigurácie YAML**.
4. Skopírujte a vložte kód zo súboru: [dashboard_config.yaml](./homeassistant/dashboard_config.yaml)
