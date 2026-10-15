AI LOCK
owner: codex
branch: codex/office-midia-page-20261015-010500
base: bea0a8ef6bdfa833e57b569122f9ba9ddcfd52e3
files:
- app-office-cloud/prepare.py
- app-office-cloud/build_mac.py
- app-office-cloud/build_mac_update.py
- app-office-cloud/build_windows.py
- app-office-cloud/installer.iss
- branding/office-midia-page/master.png
- branding/office-midia-page/AppIcon.icns
- branding/office-midia-page/AppIcon.ico
- branding/office-midia-page/README.md
expires: 2026-10-16 23:59 Europe/Madrid
reason: Approved MIDIA page logo release desktop9.4.0.4. Preserve native WPS converter and cloud logic. Same source as private MERP PR2361. No open PRs and clean master checked. Existing workflow fixed artifact alias retained in builder, workflow untouched.

status: released_on_merge
validation: Windows run38663180182 SUCCESS; verified WPS converter SHA, Go race tests, installation, XLSX launcher, agent, startup. Same source888b4a6d in MERP PR2361.
