# Změny

## 1.8.0

- **Luna se aktualizuje sama.** Doplněk už novou verzi nepřepíše starou binárkou ze `share/luna/` při každém restartu. Binárku odtud převezme jen tehdy, když nahraješ novou.
- Po vlastní aktualizaci se Luna čistě restartuje uvnitř doplňku a nezůstane viset stará verze na portu.
- Volba `no_update` je nově ve výchozím stavu vypnutá. Pokud ji máš v nastavení doplňku zapnutou, vypni ji, aby se Luna aktualizovala.
- Webové rozhraní ukazuje verzi, která skutečně běží.

## 1.7.6

- Webové rozhraní doplňku se už nepere se starou Lunou z původního repozitáře, když běží obě zároveň.

## 1.7.5

- První vydání v novém repozitáři nokturno-app/ha-addons. Verze navazuje na starý repozitář, Luna funguje stejně.
