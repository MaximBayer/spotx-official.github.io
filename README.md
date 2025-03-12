Робимо собі БЕЗКОШТОВНИЙ Spotify — вийшла модифікація, яка прибирає всю рекламу та додає фічі платної версії.

До моду входить навіть «розумне перемішування» — коли в плейлісті з’являються пісні, які ідеально тобі підходять. Крім того, він додає стильні прогрес-бари, яких немає навіть у преміум-версії. Все це БЕЗКОШТОВНО.

Для Windows потрібно ввести одну команду в Powershell:

```powershell
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SpotX-Official/spotx-official.github.io/main/run.ps1') } -new_theme"
```

Для MacOS:
```powershell
bash <(curl -sSL https://spotx-official.github.io/run.sh)
```
