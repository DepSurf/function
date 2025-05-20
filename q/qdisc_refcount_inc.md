# Function: <code>qdisc_refcount_inc</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff817fd6cd)
Location: include/net/sch_generic.h:104
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81801502)
Location: include/net/sch_generic.h:104
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8187b2bd)
Location: include/net/sch_generic.h:105
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8187f23b)
Location: include/net/sch_generic.h:105
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818cd73a)
Location: include/net/sch_generic.h:107
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818d1f80)
Location: include/net/sch_generic.h:107
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818f891a)
Location: include/net/sch_generic.h:118
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818fd312)
Location: include/net/sch_generic.h:118
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819580fc)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8195cd2b)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8198e5b0)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8199327b)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a66227)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81a6b262)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a6e2f7)
Location: include/net/sch_generic.h:120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81a7392d)
Location: include/net/sch_generic.h:120
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81a56b91)
Location: include/net/sch_generic.h:121
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81a5c394)
Location: include/net/sch_generic.h:121
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81b0f9c1)
Location: include/net/sch_generic.h:126
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81b15544)
Location: include/net/sch_generic.h:126
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81c96bec)
Location: include/net/sch_generic.h:133
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81c9c9d6)
Location: include/net/sch_generic.h:133
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81e527d3)
Location: include/net/sch_generic.h:133
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81e58e9a)
Location: include/net/sch_generic.h:133
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81eae040)
Location: include/net/sch_generic.h:133
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81eb43be)
Location: include/net/sch_generic.h:133
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff81f70ac2)
Location: include/net/sch_generic.h:134
Inline: True
Inline callers:
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
  - net/sched/sch_generic.c:attach_default_qdiscs
```
```
In net/sched/sch_api.c (ffffffff81f7708e)
Location: include/net/sch_generic.h:134
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffff800010c39e3c)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffff800010c3f550)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c0d4c11c)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (c0d5110c)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (c000000000d32df0)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (c000000000d39bf0)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffe0007ab0dc)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffe0007af268)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8192e420)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffff819330eb)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff818e7f20)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffff818ecbeb)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff8197f5b0)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffff8198427b)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_generic.c (ffffffff819a1b10)
Location: include/net/sch_generic.h:117
Inline: True
```
```
In net/sched/sch_api.c (ffffffff819a67bb)
Location: include/net/sch_generic.h:117
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
  - net/sched/sch_api.c:qdisc_graft
```
</details>
</li>
</ul>

## Differences
