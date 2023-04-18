# topshiriq vazifasi

Konfiguratsiya asosida dinakmik forma chizish taski
	Konfiguratsiya asosida dinamik forma chizish dasturini yaratish. Konfiguratsiyani masalan json fayl ko’rinishida saqlash mumkin. 
Kamida 4-5 ta kontrollardan foydalanish imkoni bo’lishi kerak. Bular textbox, datepicker, select-list, radio-button, checkbox va h.k bo’lishi mumkin. Bir biriga bog’liq select-list kontroli ham konfiguratsiyasini kiritish imkoni bo’lishi kerak. Masalan “viloyatlar” select-list tidan qaysidir viloyat tanlangan vaqt, “tumanlar” select-list tida tanlangan viloyatlarning tumanlari ko’rinishi kerakligini konfiguratsiyaga chiqarish.
Formalarning joylashuvini konfiguratsiyasi ham dinamik bo’lishi kerak. Masalan qaysidir kontrollar 1 qatorda 3 tasi, qaysidir kontrol bir qatorda bitta o’zi joylashishishi. Yoki inline forma yoki oddiy forma ko’rinishida chizishni konfiguratsiya chiqarish.



Dinamik forma konfiguratsiyasini yaratuvchi tool (ixtiyoriy)
Ushbu qism ixtiyoriy bo’lib bajarilgan taqdirda kandidantga katta “plus” bo’ladi.
Yuqoridagi 1-taskda aytilgan konfiguratsiya faylni yaratib/o’zgartirib beruvchi tool dasturni yaratish. Bunda toolbox yaratib, kerakli kontrollar ro’yxatini drag drop qilish orqali asosiy formaga olib o’tiladi. Va asosiy formdagi kontrollar uzunligi, nomi, joylashuv qatori va h.k. larni o’zgatirish imkoni bo’lishi kerak.
Saqlash tugmasi bosilganida bajarilgan ishlar konfiguratsiya faylga yartiladi/saqlanadi va bu konfiguratsiya faylni yuqoridagi 1-taskdagi dasturda chizib ko’rsatish imkoni bo’lishi kerak.





This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```


