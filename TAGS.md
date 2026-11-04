# 🏷 Справочник тегов — linux-cheats

Теги для навигации и поиска по шпаргалке. Используются в заголовках разделов и при поиске решений по симптомам. Новое значение добавляется сначала сюда.

## topic (тематика)

| Тег | Значение |
|---|---|
| `bash` | Bash: синтаксис, переменные, циклы, функции, пайпы, редиректы |
| `files-permissions` | файлы, права (chmod/chown, ACL, sticky bit, umask) |
| `processes` | процессы и сигналы (ps, top, kill, nice, systemd-юниты) |
| `systemd` | systemd: systemctl, journalctl, таймеры, unit-файлы |
| `network` | сеть: ip/ss, firewall (nftables/iptables), маршрутизация, DNS, tcpdump |
| `users` | пользователи, группы, sudo, PAM, SSH-ключи |
| `text-processing` | sed, awk, grep, cut, sort, uniq, xargs, регулярные выражения |
| `disk-lvm-raid` | диски, разделы, LVM, RAID, монтирование, fstab |
| `kernel` | ядро, модули, sysctl, загрузчик, параметры |
| `packages` | пакеты: apt/dnf/yum/pacman, репозитории,.snap/.deb |
| `containers` | контейнеры: Docker/Podman, образы, сети |
| `hardening` | усиление безопасности, аудит, fail2ban, SELinux/AppArmor |
| `recovery` | восстановление: rescue, снапшоты, бэкапы, сбитая загрузка, FS-ремонт |
| `monitoring` | мониторинг, логи, performance (iostat, vmstat, sar) |
| `interview` | вопросы для собеседований |

## type (характер команды)

| Тег | Значение |
|---|---|
| `theory` | теория, концепция |
| `basic` | 🟢 базовая безопасная команда |
| `advanced` | 🟡 продвинутая, требует понимания |
| `dangerous` | 🔴 опасно, может разрушить данные/систему |
| `tip` | 💡 совет, лайфхак |
| `scenario` | практический сценарий «сделай X» |

## severity (для опасных операций)

| Тег | Значение |
|---|---|
| `data-loss` | может уничтожить данные без подтверждения |
| `downtime` | прерывает сервис/сессии |
| `irreversible` | необратимо без бэкапа |

## Как искать
- GitHub-поиск: `repo:phaeton35/linux-cheats "симптом"` — по тексту и заголовкам.
- Практикум (28 задач) помечать `scenario`; решения — `#решение N`.
