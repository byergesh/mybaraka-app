## Privacy Policy / Политика конфиденциальности / Құпиялылық саясаты

**App name / Название приложения / Қосымша атауы:** **MyBaraka app**  
**Effective date / Дата вступления в силу / Күшіне ену күні:** December 21, 2025  
**Last Updated / Последнее обновление / Соңғы жаңарту:** March 15, 2026

---

## English

### Data Controller

**Data Controller:** Aigul Bakhytkyzy (individual)  
**Country:** Kazakhstan  
**Address:** Almaty, Radostcova-Utepova str. 250B, 24  
**Email:** support@mybaraka.app

### 1) Introduction

This Privacy Policy explains how **MyBaraka app** ("MyBaraka", "we", "our", "us") collects, uses, stores, and shares information when you use our mobile app and related services (including the AI assistant).

By using MyBaraka, you agree to this Privacy Policy.

### 2) Information we collect and store (what is saved in our database)

We store the following categories of data in our database **when you create an account and use the app**.

#### 2.1 Account and profile information
- **Account identifiers**: user ID, username.
- **Contact details**: email address, phone number (if provided).
- **Name fields**: first name, last name (if provided), and/or **display name**.
- **App preferences**:
  - language preference (en/ru/kz),
  - currency (e.g., KZT, RUB, USD, EUR, KGS, UZS),
  - monthly budget reset day (1–31),
  - usage mode (personal or business),
  - UI theme preference.
- **Avatar**: profile image (if you upload one) and its URL/path.
- **Pro subscription status**: whether your account has an active Pro plan, the plan type (free/monthly/annual), and the subscription expiry date.

#### 2.2 Authentication and verification information
- **OTP verification records** (during sign-up/verification flows): email, first/last name, phone (optional), one-time code (OTP), creation/expiry timestamps, verification status.
- **Password reset records**: reset code, creation/expiry timestamps, usage status.
- **Social sign-in identifiers** (only if you sign in with Google or Apple): the identity provider name (Google or Apple), your provider-level user ID, and the email address returned by that provider. We do not receive or store your Google or Apple password.

> Note: We do not store your plaintext password. Passwords are stored securely (hashed) by the authentication system.

#### 2.3 Financial data you create in the app
- **Transactions**: type (income/expense), amount, timestamp/date, description/comment (optional), wallet/source name (string), linked budget category (if applicable).
- **Budget categories**:
  - name, monthly budget limit, icon code, whether it is custom, whether it is active (categories can be removed/hidden).
- **Wallets/Sources** (for income sources and/or expense wallets): name, ordering, active status.
- **Goals**: goal name, target amount, current amount, and related timestamps/metadata (as applicable).
- **Subscriptions**: subscription name, price, next billing date and other related fields used to track recurring payments (as applicable).

#### 2.4 AI assistant / chat data
- **Chat messages** stored for your account: your messages and assistant responses, plus timestamps/metadata (as applicable).

#### 2.5 In-App Purchase records (Pro subscription)

When you purchase a Pro subscription through the App Store, Apple processes your payment and sends us a verification token. We receive and store the following data to manage your subscription:

- Apple transaction IDs (original and latest, assigned by Apple)
- Product ID (subscription plan identifier, e.g., monthly or annual)
- Subscription status (active, expired, revoked, or refunded)
- Subscription expiry date
- Raw transaction payload and App Store Server Notification payloads (Apple-issued cryptographic tokens used for purchase verification and subscription lifecycle management)

We do not receive or store your payment card information — Apple handles all payment processing.

#### 2.6 Generated statements (Excel/PDF exports)
- When you request an export, we **generate** an Excel/PDF file on the server and return it to you for download.
- We **do not** need to permanently store exported files in the database to provide this feature (unless required for debugging/operations; if stored, it will be stored securely and for a limited period).

#### 2.7 Technical data (device/IP/analytics)
- We do **not** use crash reporting services.
- We do **not** intentionally log IP addresses or device identifiers for tracking purposes.
- **Push notifications**: the app uses local push notifications (daily finance reminders, inactivity alerts, and upcoming subscription payment reminders). To schedule these at appropriate local times, the app reads your device's **timezone** — this is processed entirely on your device and is not stored on our servers. You can revoke notification permission at any time in your device settings.

### 3) AI assistant: data sharing with a third-party AI service

> **Important — User Consent Required**  
> Before you can use the AI assistant for the first time, the app will ask for your explicit consent to share the data described below with OpenAI. You may decline, in which case the AI assistant will not be available. You can withdraw your consent at any time by contacting us at **support@mybaraka.app** or by deleting your account.

#### 3.1 What data is sent to the AI service

MyBaraka includes an AI assistant feature powered by **OpenAI, L.L.C.** ("OpenAI"), a third-party AI service. Each time you send a message to the assistant, the following data is transmitted to OpenAI:

| Data field | Description |
|---|---|
| **Your message text** | The exact text you type into the chat input |
| **Your display name / first name** | Used to personalize responses |
| **Today's income total** | Aggregated number (e.g., "Income today: 50,000 KZT") |
| **Today's expense total** | Aggregated number (e.g., "Expenses today: 30,000 KZT") |
| **This month's income total** | Aggregated monthly figure |
| **This month's expense total** | Aggregated monthly figure |
| **Top expense categories this month** | Up to 6 categories: category name + total amount spent this month |
| **Your active budget categories** | Category name + monthly limit + amount spent this month + remaining amount |
| **Your financial goals** | Goal name + current amount + target amount |
| **Your upcoming subscriptions** | Up to 8 subscriptions: name + price + next billing date |
| **Your recent transactions** | Last 12 transactions: type (income/expense), amount, category, wallet/source, description, date and time |
| **Previous messages in the current session** | Chat history within the current conversation (up to 18 messages) for context |

The following data is **never sent** to the AI service:
- Your passwords, OTP codes, or reset codes
- Your avatar or profile photo
- Your email address or phone number
- Your Apple payment data (card details, transaction receipts)
- Transactions beyond the 12 most recent

**Data protection by OpenAI:** OpenAI is contractually committed to not using API-submitted data to train its models by default, providing a level of data protection equivalent to our own. See OpenAI's API Data Usage Policy at https://openai.com/policies/api-data-usage-policies.

#### 3.2 Who the data is sent to

The data listed above is sent to **OpenAI, L.L.C.** ("OpenAI"), a third-party AI service provider based in the United States.

- **OpenAI Privacy Policy**: https://openai.com/privacy  
- **OpenAI API Data Usage Policy**: https://openai.com/policies/api-data-usage-policies  
- OpenAI processes requests via its API. By default, **OpenAI does not use API-submitted data to train its models** (subject to their current Terms of Service — please review OpenAI's policies for the most up-to-date information).

#### 3.3 Purpose and legal basis

We send data to OpenAI solely to generate AI assistant responses at your explicit request. The legal basis for this processing is your **consent**, which you provide before first use of the AI assistant feature.

#### 3.4 Your choices

- You can **decline** to use the AI assistant — all other app features work independently without AI.
- You can **withdraw consent** at any time by contacting us at support@mybaraka.app.
- You can **delete your chat history** using the in-app reset feature (when available).

We store your chat history (your messages and the assistant's responses) in our own database so you can review past conversations. This data is deleted when you delete your account.

### 4) How we use your information

We use your information to:
- **Provide core functionality**: budgets, transactions, subscriptions, goals, and exports.
- **Personalize your experience**: language, currency, reset day, and UI preferences.
- **AI assistant** *(with your consent)*: generate helpful financial guidance by sending a limited data snapshot and your message to OpenAI (see Section 3 for the exact data fields, the recipient, and your consent options).
- **Push notifications**: send daily reminders, inactivity alerts, and upcoming subscription payment reminders (with your device permission; you can disable at any time in device settings).
- **Security and abuse prevention**: protect accounts and prevent fraud.
- **Support and troubleshooting**: respond to requests and investigate bugs.

### 5) Data sharing

We do **not** sell your personal data.

We may share data:
- **With service providers** who help us operate MyBaraka (hosting and storage infrastructure), under confidentiality obligations.
- **With OpenAI, L.L.C.** — solely to generate AI assistant responses, and only after you have given your explicit consent (see Section 3 for the exact data disclosed, the full identity of the recipient, and how to withdraw consent). OpenAI's privacy practices are governed by their own Privacy Policy at https://openai.com/privacy.
- **With Google LLC** — only when you choose Sign in with Google for authentication. An identity token is obtained through Google Sign-In to authenticate your account. Google processes authentication data per their Privacy Policy: https://policies.google.com/privacy.
- **With Apple Inc.** — only when you choose Sign in with Apple for authentication, or when verifying an in-app subscription purchase. Apple processes authentication and payment data per their Privacy Policy: https://www.apple.com/legal/privacy/.
- **If required by law** or to protect rights, safety, and security.
- **With your consent** (for example, if you explicitly connect a third-party service in the future).

### 6) Legal basis for processing

Depending on the context, we process personal data on one or more of the following legal bases:
- **Contract performance**: to create/maintain your account and provide MyBaraka features (transactions, budgets, goals, subscriptions, exports).
- **Consent**: where you provide optional information (e.g., avatar) and when you use the AI assistant feature.
- **Legitimate interests**: to secure the service, prevent abuse, and maintain the reliability of MyBaraka.
- **Legal obligation**: to comply with applicable laws and lawful requests.

### 7) Data security

We apply reasonable administrative, technical, and organizational measures to protect your data, including access controls and encrypted transport (HTTPS/TLS). No method of transmission or storage is 100% secure.

### 8) Data retention

We keep your data:
- **As long as your account is active**, and/or
- **As needed** to provide services, comply with legal obligations, resolve disputes, and enforce agreements.

You may request deletion of your account and data (see Section 9). Some records may be retained when required by law or for legitimate business purposes.

### 9) Your rights and choices

You may have the right to:
- access your data,
- correct/update profile data,
- export your data,
- request deletion of your account and associated data,
- withdraw consent (where processing is based on consent).

**Account deletion in-app:** You can initiate account deletion directly in the app: **Profile → Session → Delete account**. To confirm deletion, we may ask you to re‑authenticate (for example, enter your password). After confirmation, your account and associated data will be deleted.

Contact: **support@mybaraka.app** (we typically respond within 30 days).

### 10) Children’s privacy

MyBaraka is not intended for children under 13. We do not knowingly collect data from children under 13.

### 11) International data transfers

Your data may be processed in countries other than your own, including where our service providers operate. We take steps to protect your data in such cases.

### 12) Changes to this policy

We may update this Privacy Policy from time to time. If changes are material, we will provide notice in the app or by other reasonable means.

### 13) Contact

- **Email**: support@mybaraka.app
- **Website**: https://mybaraka.app/support  
- **Account deletion info**: https://mybaraka.app/account-deletion  
- **Address**: Almaty, Radostcova-Utepova str. 250B, 24, Kazakhstan

---

## Русский

### Оператор персональных данных (Data Controller)

**Оператор:** Aigul Bakhytkyzy (физическое лицо)  
**Страна:** Казахстан  
**Адрес:** г. Алматы, ул. Радостцова‑Утепова 250B, 24  
**Email:** support@mybaraka.app

### 1) Введение

Настоящая Политика конфиденциальности описывает, как **MyBaraka app** («MyBaraka», «мы», «наш», «нас») собирает, использует, хранит и передаёт информацию при использовании приложения и связанных сервисов (включая AI‑ассистента).

Используя MyBaraka, вы соглашаетесь с этой Политикой конфиденциальности.

### 2) Какие данные мы собираем и храним (что сохраняется в нашей базе данных)

Мы сохраняем в базе данных следующие категории данных **при создании аккаунта и использовании приложения**.

#### 2.1 Данные аккаунта и профиля
- **Идентификаторы аккаунта**: ID пользователя, username (логин).
- **Контактные данные**: email, номер телефона (если указан).
- **Имя**: имя, фамилия (если указаны) и/или **отображаемое имя (display name)**.
- **Настройки приложения**:
  - язык (en/ru/kz),
  - валюта (например KZT, RUB, USD, EUR, KGS, UZS),
  - день обновления бюджета (1–31),
  - режим использования (личный или бизнес),
  - тема интерфейса.
- **Аватар**: изображение профиля (если вы загрузили) и его URL/путь.
- **Статус подписки Pro**: наличие активной подписки Pro, тип плана (free/monthly/annual) и дата её окончания.

#### 2.2 Данные для аутентификации и верификации
- **Записи OTP‑верификации** (в процессе регистрации/подтверждения): email, имя/фамилия, телефон (опционально), OTP‑код, время создания/истечения, статус подтверждения.
- **Записи восстановления пароля**: код восстановления, время создания/истечения, статус использования.
- **Идентификаторы социального входа** (только при входе через Google или Apple): название провайдера, ID пользователя на стороне провайдера, email‑адрес, полученный от провайдера. Мы не получаем и не храним ваш пароль Google или Apple.

> Примечание: мы не храним пароль в открытом виде. Пароли хранятся безопасно (в виде хэша) средствами системы аутентификации.

#### 2.3 Финансовые данные, которые вы создаёте в приложении
- **Операции (транзакции)**: тип (доход/расход), сумма, дата/время, комментарий (опционально), кошелёк/источник (строка), связанная категория бюджета (если выбрана).
- **Категории бюджета**:
  - название, месячный лимит, код иконки, признак «своя категория», признак активности (категории могут быть удалены/скрыты).
- **Кошельки/источники**: название, порядок сортировки, активность.
- **Цели**: название цели, целевая сумма, текущая сумма и связанные метаданные/временные поля (если применимо).
- **Подписки**: название, сумма, дата следующего списания и другие поля, используемые для учёта регулярных платежей (если применимо).

#### 2.4 AI‑ассистент / чат
- **Сообщения чата** в вашем аккаунте: ваши сообщения и ответы ассистента, а также время/метаданные (если применимо).

#### 2.5 Данные о покупках через In-App Purchase (подписка Pro)

При покупке подписки Pro через App Store оплату обрабатывает Apple, которая передаёт нам токен для верификации. Мы получаем и храним следующие данные для управления вашей подпиской:

- Идентификаторы транзакций Apple (исходный и последний, присваиваются Apple)
- Product ID (идентификатор тарифного плана: monthly или annual)
- Статус подписки (active, expired, revoked, refunded)
- Дата окончания подписки
- Исходный токен транзакции и уведомления App Store Server (криптографические токены Apple, используемые для верификации и управления жизненным циклом подписки)

Данные платёжной карты нам не передаются — Apple полностью берёт на себя обработку платежей.

#### 2.6 Скачиваемые выписки (Excel/PDF)
- При запросе выписки мы **генерируем** файл Excel/PDF на сервере и отдаём его вам на скачивание.
- Мы **не обязаны** хранить файлы выписок в базе данных постоянно (если хранение потребуется для отладки/операций — оно будет ограничено по времени и защищено).

#### 2.7 Технические данные (устройство/IP/аналитика)
- Мы **не используем** сервисы crash reporting.
- Мы **не логируем намеренно** IP‑адрес и идентификаторы устройства для целей трекинга.
- **Push‑уведомления**: приложение использует локальные push‑уведомления (ежедневные напоминания, напоминания о неактивности, напоминания о предстоящих платежах по подпискам). Для правильного расписания уведомлений приложение считывает **часовой пояс** вашего устройства — эта информация обрабатывается локально и не хранится на наших серверах. Разрешение на уведомления можно отозвать в любой момент в настройках устройства.

### 3) AI‑ассистент: передача данных стороннему AI‑сервису

> **Важно — Требуется согласие пользователя**  
> Перед первым использованием AI‑ассистента приложение запросит ваше явное согласие на передачу описанных ниже данных сервису OpenAI. Вы можете отказаться — в этом случае AI‑ассистент будет недоступен. Отозвать согласие можно в любой момент, написав нам на **support@mybaraka.app** или удалив аккаунт.

#### 3.1 Какие данные передаются AI‑сервису

В каждом запросе к AI‑ассистенту сервису **OpenAI, L.L.C.** («OpenAI») передаются следующие данные:

| Поле данных | Описание |
|---|---|
| **Текст вашего сообщения** | Ровно то, что вы вводите в поле чата |
| **Отображаемое имя / имя** | Для персонализированных ответов |
| **Итог доходов за сегодня** | Агрегированное число (например, «Доход сегодня: 50 000 ₸») |
| **Итог расходов за сегодня** | Агрегированное число (например, «Расходы сегодня: 30 000 ₸») |
| **Итог доходов за текущий месяц** | Агрегированное число за месяц |
| **Итог расходов за текущий месяц** | Агрегированное число за месяц |
| **Топ категорий расходов за месяц** | До 6 категорий: название категории + сумма расходов за месяц |
| **Активные категории бюджета** | Название + месячный лимит + потрачено за месяц + остаток |
| **Финансовые цели** | Название цели + текущая сумма + целевая сумма |
| **Предстоящие подписки** | До 8 подписок: название + цена + дата следующего списания |
| **Недавние транзакции** | 12 последних: тип (доход/расход), сумма, категория, кошелёк/источник, описание, дата и время |
| **Предыдущие сообщения сессии** | История чата в текущем разговоре (до 18 сообщений) для контекста |

Следующие данные **никогда не передаются** AI‑сервису:
- Пароли, OTP‑коды, коды восстановления
- Аватар и фото профиля
- Email и номер телефона
- Данные платёжной карты Apple (реквизиты карты, квитанции транзакций)
- Транзакции за пределами 12 последних

**Защита данных на стороне OpenAI:** OpenAI по договору обязуется не использовать данные, переданные через API, для обучения своих моделей (по умолчанию), обеспечивая уровень защиты данных, эквивалентный нашему. См. политику использования данных API OpenAI: https://openai.com/policies/api-data-usage-policies.

#### 3.2 Кому передаются данные

Указанные данные передаются компании **OpenAI, L.L.C.** («OpenAI») — стороннему провайдеру AI, расположенному в США.

- **Политика конфиденциальности OpenAI**: https://openai.com/privacy  
- **Политика использования данных API OpenAI**: https://openai.com/policies/api-data-usage-policies  
- По умолчанию **OpenAI не использует данные, переданные через API, для обучения моделей** (актуальные условия — см. на сайте OpenAI).

#### 3.3 Цель и правовое основание

Данные передаются OpenAI исключительно для генерации ответов AI‑ассистента по вашему явному запросу. Правовое основание — ваше **согласие**, которое вы даёте перед первым использованием функции.

#### 3.4 Ваш выбор

- Вы можете **отказаться** от использования AI‑ассистента — остальные функции приложения работают без AI.
- Вы можете **отозвать согласие** в любой момент: support@mybaraka.app.
- Вы можете **удалить историю чата** через функцию сброса в приложении.

Мы сохраняем историю чата (ваши сообщения и ответы ассистента) в нашей базе данных. Эти данные удаляются при удалении аккаунта.

### 4) Как мы используем данные

Мы используем ваши данные для:
- **Работы приложения**: бюджеты, операции, подписки, цели, экспорт/выписки.
- **Персонализации**: язык, валюта, день обновления бюджета и т. п.
- **AI‑ассистента** *(с вашего согласия)*: генерация ответов и рекомендаций путём передачи ограниченного набора данных и вашего сообщения сервису OpenAI (точный перечень передаваемых данных, получатель и условия отзыва согласия — см. Раздел 3).
- **Push‑уведомлений**: ежедневные напоминания, уведомления о неактивности и предстоящих платежах по подпискам (требуется разрешение устройства; можно отключить в настройках в любое время).
- **Безопасности**: защита аккаунта и предотвращение злоупотреблений.
- **Поддержки и отладки**: ответы на обращения и исправление ошибок.

### 5) Передача данных

Мы **не продаём** ваши персональные данные.

Мы можем передавать данные:
- **Поставщикам услуг**, которые помогают нам поддерживать MyBaraka (инфраструктура хостинга и хранения данных), на условиях конфиденциальности.
- **Компании OpenAI, L.L.C.** — исключительно для генерации ответов AI‑ассистента и только после получения вашего явного согласия (точный перечень передаваемых данных, полные реквизиты получателя и порядок отзыва согласия — см. Раздел 3). Обработка данных на стороне OpenAI регулируется их собственной политикой конфиденциальности: https://openai.com/privacy.
- **Компании Google LLC** — только при выборе входа через Google для аутентификации. Google обрабатывает данные аутентификации согласно своей политике конфиденциальности: https://policies.google.com/privacy.
- **Компании Apple Inc.** — только при выборе входа через Apple для аутентификации или при верификации покупки через In-App Purchase. Apple обрабатывает данные аутентификации и платежей согласно своей политике конфиденциальности: https://www.apple.com/legal/privacy/.
- **По требованию закона** или для защиты прав, безопасности и предотвращения нарушений.
- **С вашего согласия** (например, если в будущем вы подключите сторонние сервисы).

### 6) Правовые основания обработки (Legal basis)

В зависимости от ситуации мы обрабатываем персональные данные на одном или нескольких основаниях:
- **Исполнение договора**: создание/ведение аккаунта и предоставление функций MyBaraka (операции, бюджеты, цели, подписки, выписки).
- **Согласие**: когда вы предоставляете необязательные данные (например, аватар) и при использовании AI‑ассистента.
- **Законный интерес**: безопасность сервиса, предотвращение злоупотреблений, поддержание стабильной работы MyBaraka.
- **Юридическая обязанность**: выполнение требований закона и законных запросов.

### 7) Безопасность

Мы применяем разумные организационные и технические меры (включая контроль доступа и HTTPS/TLS). Однако абсолютной безопасности не существует.

### 8) Сроки хранения

Мы храним данные:
- **пока ваш аккаунт активен**, и/или
- **столько, сколько необходимо** для предоставления сервисов, выполнения юридических обязанностей и защиты прав.

Вы можете запросить удаление аккаунта и данных (см. Раздел 9). Некоторые записи могут сохраняться, если этого требует закон или есть законный интерес.

### 9) Ваши права

Вы можете:
- получить доступ к данным,
- исправить/обновить данные профиля,
- экспортировать данные,
- запросить удаление аккаунта и связанных данных,
- отозвать согласие (когда обработка основана на согласии).

**Удаление аккаунта в приложении:** вы можете инициировать удаление аккаунта прямо в приложении: **Профиль → Сессия → Удалить аккаунт**. Для подтверждения удаления может потребоваться повторная аутентификация (например, ввод пароля). После подтверждения аккаунт и связанные данные будут удалены.

Контакт: **support@mybaraka.app** (обычно отвечаем в течение 30 дней).

### 10) Дети

MyBaraka не предназначено для детей младше 13 лет. Мы не собираем данные о детях младше 13 лет намеренно.

### 11) Международная обработка

Данные могут обрабатываться за пределами вашей страны (в том числе у наших поставщиков). Мы принимаем меры для защиты данных в таких случаях.

### 12) Изменения политики

Мы можем обновлять эту Политику. При существенных изменениях мы уведомим вас в приложении или иным разумным способом.

### 13) Контакты

- **Email**: support@mybaraka.app
- **Website**: https://mybaraka.app/support  
- **Удаление аккаунта**: https://mybaraka.app/account-deletion  
- **Address**: г. Алматы, ул. Радостцова‑Утепова 250B, 24, Казахстан

---

## Қазақша

### Деректер операторы (Data Controller)

**Оператор:** Aigul Bakhytkyzy (жеке тұлға)  
**Ел:** Қазақстан  
**Мекенжай:** Алматы қ., Радостцова‑Утепова к-сі 250B, 24  
**Email:** support@mybaraka.app

### 1) Кіріспе

Бұл Құпиялылық саясаты **MyBaraka app** («MyBaraka», «біз», «біздің») қолданбасын және оған байланысты қызметтерді (оның ішінде AI көмекшісін) пайдаланған кезде деректерді қалай жинайтынымызды, қолданатынымызды, сақтайтынымызды және бөлісетінімізді түсіндіреді.

MyBaraka қолданбасын пайдалану арқылы сіз осы Саясатқа келісесіз.

### 2) Қандай деректерді жинаймыз және сақтаймыз (біздің дерекқорда не сақталады)

Біз аккаунт құрғанда және қолданбаны пайдаланғанда төмендегі деректерді дерекқорда сақтаймыз.

#### 2.1 Аккаунт және профиль деректері
- **Аккаунт идентификаторлары**: пайдаланушы ID, username (логин).
- **Байланыс деректері**: email, телефон нөмірі (егер көрсетілсе).
- **Аты‑жөні**: аты, тегі (егер көрсетілсе) және/немесе **display name**.
- **Қосымша баптаулары**:
  - тіл (en/ru/kz),
  - валюта (мысалы KZT, RUB, USD, EUR, KGS, UZS),
  - бюджет жаңарту күні (1–31),
  - пайдалану режимі (жеке немесе бизнес),
  - интерфейс тақырыбы.
- **Аватар**: профиль суреті (жүктесеңіз) және оның URL/жолы.
- **Pro жазылым күйі**: белсенді Pro жоспарының бар-жоғы, жоспар түрі (free/monthly/annual) және аяқталу күні.

#### 2.2 Аутентификация және верификация деректері
- **OTP верификация жазбалары** (тіркелу/растау кезінде): email, аты/тегі, телефон (міндетті емес), OTP коды, жасалған/аяқталатын уақыты, растау статусы.
- **Құпиясөзді қалпына келтіру жазбалары**: қалпына келтіру коды, жасалған/аяқталатын уақыты, қолданылған статусы.
- **Әлеуметтік кіру идентификаторлары** (тек Google немесе Apple арқылы кірген жағдайда): провайдер атауы, провайдер тарапындағы пайдаланушы ID, провайдерден алынған email мекенжайы. Google немесе Apple құпиясөзіңіз бізге берілмейді және сақталмайды.

> Ескерту: құпиясөз ашық күйінде сақталмайды. Құпиясөздер қауіпсіз түрде (хэш) сақталады.

#### 2.3 Қаржылық деректер (сіз енгізетін)
- **Операциялар (транзакциялар)**: түрі (кіріс/шығыс), сома, күн/уақыт, түсініктеме (міндетті емес), әмиян/көз атауы (мәтін), бюджет санатымен байланысы (таңдалса).
- **Бюджет санаттары**:
  - атауы, айлық лимит, иконка коды, «өз санаты» белгісі, белсенділік белгісі (санаттар жойылып/жасырылуы мүмкін).
- **Әмияндар/көздер**: атауы, реттік тәртібі, белсенділігі.
- **Мақсаттар**: мақсат атауы, мақсат сома, ағымдағы сома және басқа метадеректер (болса).
- **Жазылымдар**: атауы, сома, келесі төлем күні және басқа өрістер (болса).

#### 2.4 AI көмекші / чат
- **Чат хабарламалары**: сіздің хабарламаларыңыз және көмекші жауаптары, сондай‑ақ уақыт/метадеректер (болса).

#### 2.5 In-App Purchase жазылым деректері (Pro жазылымы)

App Store арқылы Pro жазылымын сатып алғанда, Apple төлемді өңдейді және бізге растау токенін жібереді. Жазылымыңызды басқару үшін біз мынадай деректерді алып, сақтаймыз:

- Apple транзакция идентификаторлары (бастапқы және соңғы, Apple тарапынан тағайындалады)
- Product ID (жазылым жоспарының идентификаторы: monthly немесе annual)
- Жазылым күйі (active, expired, revoked, refunded)
- Жазылым аяқталу күні
- Бастапқы транзакция токені және App Store Server хабарландырулары (верификация және жазылым өмірлік циклін басқаруға арналған Apple криптографиялық токендері)

Төлем картасы деректері бізге берілмейді — Apple барлық төлем өңдеуін жүзеге асырады.

#### 2.6 Excel/PDF үзінді көшірмелері
- Үзінді көшірмені сұрағанда, біз файлды серверде **генерациялап**, сізге жүктеп алуға береміз.
- Біз бұл файлдарды дерекқорда тұрақты түрде сақтауға міндетті емеспіз (егер қажет болса — шектеулі мерзімге және қорғалған түрде сақталады).

#### 2.7 Техникалық деректер (құрылғы/IP/аналитика)
- Біз crash reporting/қателер аналитикасын **қолданбаймыз**.
- Біз IP‑адрес пен құрылғы идентификаторларын трекинг мақсатында **әдейі логтамаймыз**.
- **Push хабарландырулары**: қолданба жергілікті push хабарландыруларын пайдаланады (күнделікті еске салулар, белсенсіздік туралы ескертулер, жазылым төлемдері туралы алдын ала хабарландырулар). Хабарландыруларды тиісті жергілікті уақытта жіберу үшін қолданба құрылғыңыздың **уақыт белдеуін** оқиды — бұл мәлімет тек құрылғыда өңделеді және біздің серверлерде сақталмайды. Хабарландыру рұқсатын кез келген уақытта құрылғы параметрлерінде өшіруге болады.

### 3) AI көмекші: үшінші тарап AI қызметіне деректерді жіберу

> **Маңызды — Пайдаланушы келісімі қажет**  
> AI көмекшісін алғаш рет пайдаланбас бұрын, қолданба төменде сипатталған деректерді OpenAI‑ге жіберуге сіздің нақты келісіміңізді сұрайды. Бас тарта аласыз — бұл жағдайда AI көмекшісі қол жетімді болмайды. Келісімді кез келген уақытта **support@mybaraka.app** мекенжайына жазу немесе аккаунтты жою арқылы кері қайтара аласыз.

#### 3.1 AI қызметіне қандай деректер жіберіледі

Сіз AI көмекшіне хабарлама жіберген сайын, **OpenAI, L.L.C.** («OpenAI») қызметіне мынадай деректер беріледі:

| Деректер өрісі | Сипаттама |
|---|---|
| **Хабарламаңыздың мәтіні** | Чат өрісіне енгізген мәтін |
| **Атыңыз / отображаемое атыңыз** | Жекелендірілген жауаптар үшін |
| **Бүгінгі кіріс жиынтығы** | Жиынтық санмен (мысалы, «Бүгінгі кіріс: 50 000 ₸») |
| **Бүгінгі шығыс жиынтығы** | Жиынтық санмен (мысалы, «Бүгінгі шығыс: 30 000 ₸») |
| **Осы айдағы кіріс жиынтығы** | Айлық жиынтық сан |
| **Осы айдағы шығыс жиынтығы** | Айлық жиынтық сан |
| **Айдағы үздік шығыс санаттары** | 6-ға дейін: санат атауы + осы айдағы шығын сомасы |
| **Белсенді бюджет санаттары** | Атауы + айлық лимит + айдағы шығын + қалдық |
| **Қаржылық мақсаттар** | Мақсат атауы + ағымдағы сома + мақсат сомасы |
| **Алдағы жазылымдар** | 8-ге дейін: атауы + бағасы + келесі төлем күні |
| **Соңғы транзакциялар** | Соңғы 12: түрі (кіріс/шығыс), сомасы, санаты, әмиян/көз, сипаттама, күні мен уақыты |
| **Ағымдағы сессияның алдыңғы хабарламалары** | Контекст үшін чат тарихы (18 хабарламаға дейін) |

Мынадай деректер AI қызметіне **ешқашан жіберілмейді**:
- Құпиясөздер, OTP кодтары, қалпына келтіру кодтары
- Аватар және профиль фотосы
- Email мекенжайы және телефон нөмірі
- Apple төлем картасы деректері (карта реквизиттері, чектер)
- Соңғы 12 транзакциядан тыс операциялар

**OpenAI тарапындағы деректер қорғауы:** OpenAI шарт бойынша API арқылы жіберілген деректерді үлгілерді оқыту үшін пайдаланбауға міндеттенген (әдепкі бойынша), бұл біздің деректер қорғауымызбен бірдей деңгейді қамтамасыз етеді. OpenAI API деректерін пайдалану саясатын қараңыз: https://openai.com/policies/api-data-usage-policies.

#### 3.2 Деректер кімге жіберіледі

Жоғарыда аталған деректер АҚШ‑та орналасқан үшінші тарап AI провайдері — **OpenAI, L.L.C.** («OpenAI») компаниясына жіберіледі.

- **OpenAI Құпиялылық саясаты**: https://openai.com/privacy  
- **OpenAI API деректерін пайдалану саясаты**: https://openai.com/policies/api-data-usage-policies  
- Әдепкі бойынша **OpenAI API арқылы жіберілген деректерді модельдерді үйрету үшін пайдаланбайды** (ең өзекті шарттар үшін OpenAI сайтын қараңыз).

#### 3.3 Мақсат және құқықтық негіз

Деректер OpenAI‑ге тек сіздің нақты сұрауыңыз бойынша AI көмекші жауаптарын жасау үшін жіберіледі. Өңдеудің құқықтық негізі — сіз функцияны алғаш рет пайдаланбас бұрын беретін **келісіміңіз**.

#### 3.4 Сіздің таңдауыңыз

- AI көмекшісін пайдаланудан **бас тарта аласыз** — қолданбаның барлық басқа функциялары AI‑сыз жұмыс істейді.
- Келісімді кез келген уақытта **кері қайтара аласыз**: support@mybaraka.app.
- Қолданбадағы «reset» функциясы арқылы **чат тарихын жоя аласыз**.

Чат тарихы (сіздің хабарламаларыңыз және көмекші жауаптары) біздің дерекқорда сақталады. Аккаунтты жойған кезде бұл деректер де жойылады.

### 4) Деректерді қалай қолданамыз

Біз деректерді:
- қолданбаның негізгі функцияларын іске асыруға,
- тәжірибені дараландыруға,
- **AI көмекшінің жауаптарын жасауға** *(сіздің келісіміңізбен)*: хабарламаңыз бен шектеулі деректер жиынын OpenAI қызметіне жіберу арқылы (жіберілетін деректердің нақты тізімі, алушы және келісімді кері қайтару шарттары — 3‑бөлімде),
- **Push хабарландыруларын жіберуге**: күнделікті еске салулар, белсенсіздік туралы ескертулер және жазылым төлемдері туралы алдын ала хабарландырулар (құрылғы рұқсаты қажет; кез келген уақытта параметрлерде өшіруге болады),
- қауіпсіздік пен алаяқтықтың алдын алуға,
- қолдау және ақауларды түзетуге қолданамыз.

### 5) Деректерді бөлісу

Біз деректерді сатпаймыз.

Біз деректерді келесі жағдайларда бөлісуіміз мүмкін:
- **Қызмет көрсетушілермен** (хостинг және деректерді сақтау инфрақұрылымы) — құпиялылық міндеттемелері негізінде.
- **OpenAI, L.L.C. компаниясымен** — тек AI көмекші жауаптарын жасау үшін және тек сіздің нақты келісіміңізден кейін (жіберілетін деректердің толық тізімі, алушының толық атауы және келісімді кері қайтару тәртібі — 3‑бөлімде). OpenAI деректерді өздерінің Құпиялылық саясатына сәйкес өңдейді: https://openai.com/privacy.
- **Google LLC компаниясымен** — тек Google арқылы кіруді таңдаған жағдайда, аутентификация мақсатында. Google аутентификация деректерін өз Құпиялылық саясатына сәйкес өңдейді: https://policies.google.com/privacy.
- **Apple Inc. компаниясымен** — тек Apple арқылы кіруді таңдаған жағдайда немесе In-App Purchase арқылы жазылымды верификациялау кезінде. Apple аутентификация және төлем деректерін өз Құпиялылық саясатына сәйкес өңдейді: https://www.apple.com/legal/privacy/.
- **Заң талабы бойынша** немесе құқық/қауіпсіздікті қорғау үшін.
- **Сіздің нақты келісіміңізбен** (мысалы, болашақта үшінші тарап қызметтерін қоссаңыз).

### 6) Өңдеудің құқықтық негіздері (Legal basis)

Жағдайға байланысты біз деректерді мына негіздердің бірімен (немесе бірнешеуімен) өңдейміз:
- **Келісімшартты орындау**: аккаунт ашу және MyBaraka функцияларын ұсыну (операциялар, бюджет, мақсаттар, жазылымдар, үзінді көшірмелер).
- **Келісім (consent)**: міндетті емес деректер (мысалы, аватар) және AI көмекшісін пайдаланған кезде.
- **Заңды мүдде**: сервистің қауіпсіздігі, теріс пайдалануды болдырмау, тұрақты жұмысын қамтамасыз ету.
- **Заң талаптары**: қолданыстағы заң талаптарын орындау.

### 7) Қауіпсіздік

Біз қолжетімділікті бақылау және қауіпсіз байланыс (HTTPS/TLS) сияқты ұйымдастырушылық және техникалық шараларды қолданамыз. Дегенмен, деректердің толық қауіпсіздігіне кепілдік берілмейді.

### 8) Сақтау мерзімі

Біз деректерді:
- аккаунт белсенді болғанша, және/немесе
- қызметтерді көрсету, заң талаптарын орындау және қауіпсіздікті қамтамасыз ету үшін қажет уақыт ішінде сақтаймыз.

### 9) Құқықтарыңыз

Сіз деректерге қол жеткізуге, түзетуге/жаңартуға, экспорттауға, аккаунтты және деректерді жоюды сұрауға құқылы болуыңыз мүмкін.  
Егер өңдеу келісімге негізделсе, келісімді кері қайтарып ала аласыз.

**Аккаунтты қолданба ішінде жою:** аккаунтты жоюды қолданба ішінде бастай аласыз: **Профиль → Сессия → Аккаунтты жою**. Растау үшін қайта аутентификация сұралуы мүмкін (мысалы, құпиясөзді енгізу). Расталғаннан кейін аккаунт және оған байланысты деректер жойылады.

Байланыс: **support@mybaraka.app** (әдетте 30 күн ішінде жауап береміз).

### 10) Балалар

MyBaraka 13 жасқа толмаған балаларға арналмаған. Біз 13 жасқа толмаған балалар туралы деректерді әдейі жинамаймыз.

### 11) Халықаралық өңдеу

Деректер сіздің еліңізден тыс жерде (қызмет көрсетушілердің инфрақұрылымында) өңделуі мүмкін. Біз мұндай жағдайларда деректерді қорғау шараларын қолданамыз.

### 12) Саясат өзгерістері

Біз бұл Саясатты мезгіл‑мезгіл жаңарта аламыз. Маңызды өзгерістер туралы қолданбада немесе басқа ақылға қонымды тәсілмен хабарлаймыз.

### 13) Байланыс

- **Email**: support@mybaraka.app  
- **Website**: https://mybaraka.app/support  
- **Аккаунтты жою**: https://mybaraka.app/account-deletion  
- **Address**: Алматы қ., Радостцова‑Утепова к-сі 250B, 24, Қазақстан

