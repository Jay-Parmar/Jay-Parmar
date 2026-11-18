# Jay Parmar

I'm a software engineer in New Delhi. At ESSI Integrated Technologies, I design backend systems and manage AWS infrastructure. Moving releases to Docker and GitLab CI/CD gave our team **70% faster updates**. Previously, I built Django APIs and tuned PostgreSQL queries for a recruitment platform serving **200k+ daily users**.

[LinkedIn](https://www.linkedin.com/in/jayparmar789/) · [Email](mailto:jayparmar789@gmail.com) · [GitLab](https://gitlab.com/jayparmar789) · [Portfolio source](https://github.com/Jay-Parmar/JayParmar)

## Selected projects

### hirejutsu

Each morning, hirejutsu ranks job openings against your résumé and explains its picks. Python adapters normalize listings from 15 applicant tracking systems into a local SQLite database. The app marks a posting closed only after a successful scan of the company's board confirms the opening has disappeared.

[Source](https://github.com/Jay-Parmar/hirejutsu) · [Example daily run](https://github.com/Jay-Parmar/hirejutsu/blob/main/docs/playthrough.md)

### PocketDisco

PocketDisco is an Android alpha for listening parties. Friends can join a private room, chat, and preview audio on their own phones. FastAPI writes chat messages to PostgreSQL before publishing updates through Redis. A phone that misses a WebSocket update can recover the member list and recent chat from a versioned room snapshot.

[App and API](https://github.com/Jay-Parmar/PocketDisco/tree/feature/mobile-ui-walkthrough) · [Room protocol](https://github.com/Jay-Parmar/PocketDisco/blob/fb44e2d6edf7f3d96d4d1b86e1b251402b5c3932/docs/08-mobile-alpha.md) · [Android walkthrough (PDF)](https://github.com/Jay-Parmar/PocketDisco/blob/fb44e2d6edf7f3d96d4d1b86e1b251402b5c3932/docs/walkthrough/PocketDisco-Walkthrough.pdf)

### Hold My Files

Guests on the same Wi-Fi can download files from an Android phone using a browser and a PIN. The owner picks which folders to share. A foreground service runs the read-only Ktor server, so downloads can continue while the owner uses another app. Stopping the server invalidates every guest session and file link.

[Android MVP](https://github.com/Jay-Parmar/HoldMyFiles/tree/codex/android-mvp) · [System architecture](https://github.com/Jay-Parmar/HoldMyFiles/blob/2fbaaf4ab482be138cf5a8266ed72e94322001be/docs/architecture.md)

### ThatsMyFace

ThatsMyFace helps friends find photos of themselves after a group event. In this Android prototype, friends can opt in to share face templates derived from their selfies over Nearby Connections. Matching runs on the phone holding the photos. Friends can browse previews and request an original, which the owner approves before transfer.

[Android prototype](https://github.com/Jay-Parmar/ThatsMyFace/tree/feat/field-test-walkthrough) · [Two-phone walkthrough (PDF)](https://github.com/Jay-Parmar/ThatsMyFace/blob/1e0c3517cc6d751a8a2aa60fed8eac71c1a46349/docs/ThatsMyFace-Walkthrough.pdf)

### FoodHub Sniffer

FoodHub gives a café one order board for Zomato and Swiggy using the notifications their Android apps already send. It saves the raw events locally and rebuilds order cards from them in Kotlin. If an order ID arrives on a later update, the board links the first alert to the same card.

[Source](https://github.com/Jay-Parmar/FoodHub) · [Order grouping tests](https://github.com/Jay-Parmar/FoodHub/blob/main/app/src/test/java/com/foodhub/sniffer/OrderBoardTest.kt)
