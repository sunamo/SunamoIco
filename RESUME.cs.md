---
schema_version: 11
type: library
category_override: none
file_count: 5
file_extensions: md:2, csproj:1, noext:1, yml:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 21
total_lines: 0
metrics_lm: 2026-10-01 16:40:23
move_to_legacy_percent: 80
description_updated: 2026-10-01
links_updated: 2026-10-01
github_source_url: not found
origin_status: found
origin_checked: 2026-10-01
article_source_url: not run
article_status: pending
article_checked: not run
last_build_ok: yes
last_build_date: 2026-10-02
last_tests_run_date: not run
covered_lines: 0
---

## Description

Prázdná skořápka projektu SunamoIco.standard (net6.0-windows, odkaz na System.Drawing.Common 4.7.0) převzatá ze starého repa standardWithoutDep. Neobsahuje žádné zdrojové soubory, jen definici projektu a Taskfile. Má být místem pro budoucí kód práce s ikonami.

## Původ zdrojáků

Staženo z GitHubu: **ne** — vlastní repo (`sunamo/SunamoIco` na GitHubu), obsah převzat ze starého vlastního repa při reorganizaci.

- Ověřeno: `git remote -v` (`git@github.com:sunamo/SunamoIco.git`, vlastní účet), `git log` (7 commitů od 2026-09-29, autoři Radek Jančík/smutekutek, commit „Prevzeti obsahu z standardWithoutDep“), v repu není žádný zdrojový soubor k porovnání.
- `gh search repos "SunamoIco"` vrátil jen vlastní repo `sunamo/SunamoIco`; hash porovnání nemá smysl, protože repo neobsahuje kód.

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **80 %** — bez kódu, jen prázdná definice projektu.

- Obsahuje 4 soubory (csproj, Taskfile, `.gitignore`, RESUME) a žádné zdrojáky.
- Vzniklo teprve 2026-09-29 při reorganizaci, jiný obsah nemá.
- Smazat, pokud se práce s ikonami nezačne implementovat.

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné
