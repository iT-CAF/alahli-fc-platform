<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/projects/alahli-fc-platform-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/projects/alahli-fc-platform-light.png">
  <img alt="منصة جماهير الأهلي — Al-Ahli Fan Platform" src="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/projects/alahli-fc-platform-dark.png" width="100%">
</picture>

<p>
  <img alt="Live" src="https://img.shields.io/badge/Live-3E8E7E?style=flat-square">
  <img alt="Laravel" src="https://img.shields.io/badge/Laravel-1A2024?style=flat-square&logo=laravel&logoColor=E8A33D">
  <img alt="Livewire" src="https://img.shields.io/badge/Livewire-1A2024?style=flat-square&logo=livewire&logoColor=E8A33D">
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-1A2024?style=flat-square&logo=flutter&logoColor=E8A33D">
  <img alt="Swift" src="https://img.shields.io/badge/Swift-1A2024?style=flat-square&logo=swift&logoColor=E8A33D">
  <a href="https://alahli.it-caf.com"><img alt="alahli.it-caf.com" src="https://img.shields.io/badge/alahli.it--caf.com-E8A33D?style=flat-square"></a>
</p>

<div dir="rtl" align="right">

### ‹ مركز مباريات مباشر، ومواعيد، وإشعارات لحظية لجماهير النادي الأهلي — ويب وiOS وأندرويد.

منصة رياضية عربية أولًا لجماهير النادي الأهلي السعودي: تعرض المباريات القادمة والنتائج والترتيب وتاريخ النادي، مع صفحة مباشرة تتحوّل تلقائيًا إلى مركز مباراة كامل أثناء اللعب. عُرضت الفكرة على إدارة النادي ورحّبت بها، وطُوِّرت بالتعاون مع الطاقم التقني.

</div>

**Live match centre, fixtures and push alerts for Al-Ahli fans — web, iOS and Android.**

An Arabic-first sports platform for Al-Ahli Saudi FC supporters. It covers fixtures, results, standings and club history, and its live page turns into a full match centre while a game is in play. The idea was presented to the club's management, who welcomed it, and was refined with their technical staff.

## `>` Features · المزايا

| Feature | الميزة |
|:--|--:|
| Live match centre (365scores-style): events, stats, line-ups, momentum | مركز مباراة مباشر بنمط 365scores: أحداث، إحصائيات، تشكيلات، Match Momentum |
| Shareable match cards rendered as images | بطاقات مباريات قابلة للمشاركة كصورة |
| Single interactive calendar with Saudi public events | تقويم تفاعلي واحد مع المناسبات السعودية |
| Team tabs, cup draw brackets, overall/home/away tables | صفحات الفريق والقرعة والترتيب (عام/داخل/خارج) |
| Duplicate-safe goal alerts (direct APNs + OneSignal driver) | إشعارات أهداف بدون تكرار (APNs مباشر + OneSignal) |
| Flutter app plus a native Swift app with Live Activities & widgets | تطبيق Flutter + تطبيق Swift أصلي مع Live Activities وودجت |
| Bilingual UI with automatic RTL/LTR switching | واجهة ثنائية اللغة تقلب الاتجاه تلقائيًا |

## `<>` Architecture · البنية

| Layer | Details |
|:--|:--|
| **Backend** | Laravel · Livewire (wire:navigate) · Tailwind |
| **Data** | Sportmonks Football API v3 · seasons 2023/24 → today |
| **Push** | APNs (JWT/ES256 over HTTP/2) · OneSignal · pushed_events ledger |
| **Mobile** | Flutter (iOS/Android) · Swift/SwiftUI (iPhone, iPad, Mac, Watch) |
| **Quality** | 15 feature tests guarding the notification pipeline |


## `$` Repository · المستودع

> [!NOTE]
> This repository is a project showcase. The source code is private.
> For a walkthrough or demo, reach out via [it-caf.com](https://it-caf.com).
>
> <span dir="rtl">هذا المستودع للتعريف بالمشروع، والكود المصدري خاص. للعرض التجريبي تواصل عبر it-caf.com.</span>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/footer-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/footer-light.png">
  <img alt="{ build quietly } — iT CAF" src="https://raw.githubusercontent.com/iT-CAF/iT-CAF/main/assets/footer-dark.png" width="100%">
</picture>

<p align="center"><sub>Built by <a href="https://github.com/iT-CAF">Abdulrhman Alyazidi · iT CAF</a> — <a href="https://it-caf.com">it-caf.com</a></sub></p>
