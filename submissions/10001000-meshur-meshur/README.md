# Nokta Away Mission — Submission

**Track Seçimi:** Track A — Dot Capture & Enrich
**Expo QR Kodu / Linki:** exp://exp.host/@meshurai/nokta-track-a (Mock Link)
**60 sn Demo Video:** https://youtu.be/dummy-link

## Karar Defteri (Decision Log)

- **UI Kurgusu:** Karpathy'nin "autoresearch" pattern'ından ilham alınarak, karmaşık formlar yerine doğrudan ardışık sorular soran bir chat UI kullandım (`App.tsx`). Bu sayede kullanıcının bilişsel yükü azaldı.
- **AI Yaklaşımı:** API key sorunu olmaması için ilk versiyonda (v0.1) mock sorular tanımlandı, bu sayede CI akışında API timeout sorunları yaşanması engellendi.
- **Spec Sayfası:** Çıkarımı anında bir "artifact" ekranına dökebilmek ve kopyalanabilir kılmak için ayrı bir ScrollView component tanımlandı.

## Bonuslar
- [ ] +10 Çılgınlık (Şu an yok)
- [x] +3 APK teknik tamlık bonusu (`app-release.apk` teslimata eklendi)
