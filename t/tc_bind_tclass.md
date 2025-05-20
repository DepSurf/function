# Function: <code>tc_bind_tclass</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tc_bind_tclass(struct Qdisc *q, u32 portid, u32 clid, long unsigned int new_cl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187bfe0)
Location: net/sched/sch_api.c:1664
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff8187bfe0-ffffffff8187c0cd: tc_bind_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tc_bind_tclass(struct Qdisc *q, u32 portid, u32 clid, long unsigned int new_cl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ce870)
Location: net/sched/sch_api.c:1802
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818ce870-ffffffff818ce95f: tc_bind_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tc_bind_tclass(struct Qdisc *q, u32 portid, u32 clid, long unsigned int new_cl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818f9b20)
Location: net/sched/sch_api.c:1899
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818f9b20-ffffffff818f9c17: tc_bind_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tc_bind_tclass(struct Qdisc *q, u32 portid, u32 clid, long unsigned int new_cl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819598b0)
Location: net/sched/sch_api.c:1912
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff819598b0-ffffffff819599ce: tc_bind_tclass (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff819920e3)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a6a4c9)
Location: net/sched/sch_api.c:1961
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a72bf6)
Location: net/sched/sch_api.c:1962
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81a5b544)
Location: net/sched/sch_api.c:1963
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81b14704)
Location: net/sched/sch_api.c:1964
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81c9babb)
Location: net/sched/sch_api.c:1955
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81e57fd1)
Location: net/sched/sch_api.c:1973
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81eb397a)
Location: net/sched/sch_api.c:2047
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81f7645c)
Location: net/sched/sch_api.c:2104
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffff800010c3e690)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tc_bind_tclass(struct Qdisc *q, u32 portid, u32 clid, long unsigned int new_cl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4d4b8)
Location: net/sched/sch_api.c:1951
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
c0d4d4b8-c0d4d554: tc_bind_tclass (STB_LOCAL)
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
In net/sched/sch_api.c (c000000000d38938)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffe0007ae6ce)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff81931f53)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff818eba53)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff819830e3)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffffffff819a5633)
Location: net/sched/sch_api.c:1951
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
