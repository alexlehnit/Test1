# Roadmap Driftwood

Stand 17.10.2026 (Entwurf). Jede Phase läuft Entwicklung → Integration → Test. Obertasks und Aufgaben stehen in den [Issues](../../issues?q=label%3Aobertask), Termine in den [Meilensteinen](../../milestones).

```mermaid
gantt
    title Driftwood – Phasenplan bis zur Abgabe
    dateFormat YYYY-MM-DD
    axisFormat %d.%m.

    section Phase 0 Start
    Organisation, Unity-Projekt, Schnittstellen :p0, 2026-10-17, 2026-10-26
    Konzeptvorstellung                           :milestone, m0, 2026-10-27, 0d

    section Phase 1 Prototyp
    Entwicklung O1–O5      :p1d, 2026-10-19, 2026-11-05
    Integration 1          :p1i, 2026-11-05, 2026-11-09
    Testphase 1            :crit, p1t, 2026-11-09, 2026-11-16
    Starterinsel spielbar  :milestone, m1, 2026-11-15, 0d

    section Phase 2 Features
    Entwicklung O1–O5      :p2d, 2026-11-16, 2026-11-26
    Integration 2          :p2i, 2026-11-26, 2026-11-30
    Testphase 2            :crit, p2t, 2026-11-30, 2026-12-04
    Spiel durchspielbar    :milestone, m2, 2026-12-03, 0d

    section Phase 3 optional
    Nice-to-have (nur wenn Zeit) :done, p3, 2026-11-26, 2026-12-04

    section Endphase
    Nur Fixen und Testen   :crit, end, 2026-12-04, 2026-12-18
    Testversion fertig     :milestone, m3, 2026-12-17, 0d
    Letzter Test vor Evaluierung :milestone, t18, 2026-12-18, 0d

    section Evaluierung und Bericht
    Evaluierung planen     :ev0, 2026-11-26, 2026-12-04
    Evaluierung durchführen und auswerten :ev, 2027-01-05, 2027-01-19
    Projektbericht         :ber, 2027-01-05, 2027-02-01
    Probe-Abschlussvortrag :milestone, pv, 2027-01-26, 0d
    Abgabe Projektbericht  :milestone, m4, 2027-01-31, 0d
```

| Phase | Zeitraum | Meilenstein |
|---|---|---|
| 0 Start | 17.–26.10. | Konzept vorstellen 27.10. |
| 1 Prototyp | Entwicklung 19.10.–04.11., Integration 05.–08.11., Test 09.–15.11. | Starterinsel spielbar 15.11. |
| 2 Features | Entwicklung 16.–25.11., Integration 26.–29.11., Test 30.11.–03.12. | Spiel durchspielbar 03.12. |
| 3 Nice-to-have | nur wenn Phase 2 früher fertig ist, Integration spätestens 03.12. | – |
| Endphase | 04.–17.12., nur Fixen und Testen | Testversion fertig 17.12. |
| Evaluierung und Bericht | ab 05.01.2027 | Abgabe Projektbericht 31.01.2027 |
