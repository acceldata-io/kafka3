---
type: Cherry-pick Log
title: Kafka3 Ported Commits
description: Commits ported from rel/3.3.6.4-1, manually reviewed ODP changes except for CVE/OSV or general version bump-ups.
resource: https://docs.google.com/spreadsheets/d/19auGdoHyq0gDv_XZA6-uq-0ujYVHRBBagEjdPOpcVFk/edit?gid=717730257#gid=717730257
tags: [Kafka3, cherry-pick]
timestamp: 2026-07-25T00:00:00Z
---

| hash       | date       | author          | message                                                                |
| ---------- | ---------- | --------------- | ---------------------------------------------------------------------- |
| eea708809e | 2026-04-22 | Dahyun (Dany)   | ODP-6317 : Integrate Aiven Tiered Storage Plugin into ODP Kafka3 (#33) |
| 5cbdeaf124 | 2026-04-21 | Basapuram Kumar | ODP-6387: Add camel connector dependency jars into kafka libs (#36)    |
| 858e89f64a | 2024-12-10 | basapuram-kumar | ODP-2770: Refactor Kafka3 to use ambari-python-wrap for all scripts    |
| fe69ba9b9e | 2024-11-20 | basapuram-kumar | ODP-2577: kafka mirrormaker2 observability for jmx port (#12)          |
| 48464e7d06 | 2024-11-20 | basapuram-kumar | ODP-2519: kafka connect observability for jmx (#9)                     |
| 4899b3c5e7 | 2024-08-07 | Sourabh Dilraj  | ODP-1911: Changed KAFKA_HOME for kafka connect and mirrormaker         |