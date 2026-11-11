<div align="center">

# MongoDB / Commerce Cohort Analytics

**Aggregation, queries and commerce data modeling in MongoDB.**

`JavaScript` · Research / engineering project · Source-first

</div>

---

## Mission

Indexed event collections, per-user funnel state via `$group/$addToSet`, cohort conversion rates and pipeline assertions. Includes a synthetic fixture and avoids requiring any cloud connection.

## Run / reproduce

```bash
mongosh --file pipeline.js
```

## Files and responsibilities

| Path | Description |
| :--- | :--- |
| [`README.md`](./README.md) | Project documentation |
| [`pipeline.js`](./pipeline.js) | Implementation or example data |

## What to investigate

- Inspect the data, assumptions and program entry point.
- Modify inputs and observe the effect on behavior.
- Look for error cases and compare results with any included tests.

## Responsible interpretation

This is an educational demonstration, not a production-grade analytics, security or financial advice system. Use synthetic or permitted test data; review dependencies and limitations before reusing the implementation.

<details><summary><strong>Preserved original project notes</strong></summary>

# MongoDB / Commerce Cohort Analytics

Indexed event collections, per-user funnel state via `$group/$addToSet`, cohort conversion rates and pipeline assertions. Includes a synthetic fixture and avoids requiring any cloud connection.

```bash
mongosh --file pipeline.js
```

Use a local MongoDB 6+ server and shell. **Will replace only the `sp_analytics_demo` fixture database's `events` and `orders` collections**.

</details>

---

<sub>Browse the [rest of the project collection](https://github.com/sharanyapal?tab=repositories).</sub>
