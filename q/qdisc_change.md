# Function: <code>qdisc_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81745461)
Location: net/sched/sch_api.c:1027
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b2314)
Location: net/sched/sch_api.c:1027
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e1ac4)
Location: net/sched/sch_api.c:1044
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8180103c)
Location: net/sched/sch_api.c:1043
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187ed6c)
Location: net/sched/sch_api.c:1125
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818d1cb6)
Location: net/sched/sch_api.c:1217
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fd03a)
Location: net/sched/sch_api.c:1300
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195c9f4)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81992f44)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int qdisc_change(struct Qdisc *sch, struct nlattr **tca, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a69b00)
Location: net/sched/sch_api.c:1316
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81a69b00-ffffffff81a69c6d: qdisc_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int qdisc_change(struct Qdisc *sch, struct nlattr **tca, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a71d10)
Location: net/sched/sch_api.c:1317
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81a71d10-ffffffff81a71e7d: qdisc_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5c096)
Location: net/sched/sch_api.c:1317
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b15246)
Location: net/sched/sch_api.c:1323
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9c88f)
Location: net/sched/sch_api.c:1314
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e58d53)
Location: net/sched/sch_api.c:1339
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb44a0)
Location: net/sched/sch_api.c:1372
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f77170)
Location: net/sched/sch_api.c:1401
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3f324)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d50e10)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d39968)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007af188)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81932db4)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ec8b4)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81983f44)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a6484)
Location: net/sched/sch_api.c:1306
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
