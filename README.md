# Автоматическое закрытие окна / Auto Close Window Page

## 🇷🇺 Описание

Это простая HTML-страница, предназначенная для автоматического закрытия вкладки, если она была открыта программно (например, из JavaScript или userscript-а).

Она может использоваться, например:
- для **перенаправления пользователей с вредоносных или фишинговых сайтов**;
- для **создания ловушки** в userscript-ах (например, Violetmonkey/Tampermonkey);
- для **тестирования поведения браузеров** при попытке `window.close()`.

> ⚠️ Обратите внимание: современные браузеры **не позволяют закрывать окна**, если они **не были открыты скриптом** (`window.open`). Поэтому, если пользователь сам открыл вкладку, `window.close()` не сработает.

---

## 🇬🇧 Description

This is a simple HTML page designed to automatically close the browser tab if it was opened programmatically (e.g., via JavaScript or a userscript).

It can be used, for example:
- to **redirect users away from malicious or phishing websites**;
- to **create a "trap" page** in userscripts (e.g., for Violetmonkey/Tampermonkey);
- to **test browser behavior** when calling `window.close()`.

> ⚠️ Please note: Modern browsers **do not allow scripts to close tabs** unless they were **opened via `window.open`**. If the user opened the tab manually, `window.close()` will not work.
