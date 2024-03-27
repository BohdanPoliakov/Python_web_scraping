# Euronics iPhone Datu Izguve

## Uzdevums

Šī programmatūra ir izstrādāta, lai ļautu lietotājam ērti iegūt informāciju par iPhone produktiem no Euronics tīmekļa vietnes. Uzdevums šai programmā ir sniegt iespēju lietotājam norādīt konkrētu iPhone modeļa nosaukumu, un pēc tam programmā tiks parādīti visi saistītie produkti ar to saistītajiem detalizētiem datiem. Programmā tiks attēloti tālruņa varianti ar līdzīgiem nosaukumiem, piedāvājot lietotājam vizuālu priekšstatu par produktiem, iekļaujot attēlu, cenu un saiti uz preci. Tāpat programma nodrošinās iespēju izveidot Excel failu, kurā būs iekļauti visi iegūtie produkti no Euronics tīmekļa vietnes.

## Python Bibliotēkas

Projekts izmanto vairākas Python bibliotēkas:

- `requests` - Tiešsaistes datu ieguve.
- `BeautifulSoup` - HTML analīze un datu izguve.
- `dataclasses` - Vienkārša sintakse datu klasēm .
- `xlsxwriter` - Excel failu veidošana un datu ievietošana.

## Programmatūras Izstrādes Gaita

1. **Datu Ieguve:** Izmantojot `requests` un `BeautifulSoup`, tiek iegūti dati no Euronics tīmekļa vietnes.
2. **Datu Apstrāde:** Dati tiek attīrīti un formatēti, izmantojot funkcijas kā `remove_extra_spaces`, `format_price` un `three_symbols_price`.
3. **Datu Saglabāšana:** Izstrādāta funkcija `create_excel_file`, kas saglabā apstrādātos datus Excel failā.

## Video Par Programmas Darbību
Mūsu Programmas Darbības Video
Piemērs:
https://failiem.lv/f/drushmgpj6

## Programmas Izmantošana

Programmu iespējams izmantot, ievadot komandu terminālī:

```bash
2.py "iphone_model"
Kur "iphone_model" ir vēlamā iPhone modeļa nosaukums.

Ja vēlaties iegūt informāciju par iPhone 11, izmantojot programmu, ievadiet šādu komandu:
python 2.py iPhone 11

## Biblioteka

Lai varētu izpildīt programmu, ir nepieciešams instalēt šādas atkarības:
pip install requests
pip install beautifulsoup4
pip install xlsxwriter


