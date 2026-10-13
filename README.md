# writeups

Разборы задач, лабораторий и собственных проектов. Записи о том,
**как искалось**: какие были гипотезы, какие не подтвердились, что оказалось настоящей
подсказкой и как это чинить в реальном приложении.

Формат — [`TEMPLATE.md`](./TEMPLATE.md).

## Разборы

| | Классы | Контекст |
|---|---|---|
| [**Template injection через ключи map → SSRF → IDOR**](./2025-ctfcup-trustmebroker.md) | template injection, SSRF, IDOR | Go/Fiber + headless Chrome. Санитизация покрывала значения и пропускала имена полей |
| [**GOAD Light: от null-сессии до корня леса**](./goad-light-full-chain.md) | AD, AS-REP Roasting, Kerberoasting, `SeImpersonatePrivilege`, обход Defender, SID History | Восемь шагов, ни одного CVE |
| [**Как я чинил безопасность собственного магазина**](./marellshop-hardening.md) | secrets management, XSS, CSP, attack surface | AppSec со стороны того, кто чинит и платит за простой |
| [**Цепочка из пяти примитивов, которая не привела к флагу**](./web-duckerz-negative-result.md) | DOM XSS, postMessage, cross-origin shaping | Разбор нерешённой задачи |

## Лицензия

CC BY 4.0 — пользуйтесь со ссылкой.
