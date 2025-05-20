# Function: <code>tc_skip_sw</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81995c01)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81a6cb61)
Location: include/net/pkt_cls.h:626
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81a75511)
Location: include/net/pkt_cls.h:676
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81a5eea1)
Location: include/net/pkt_cls.h:676
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81b18151)
Location: include/net/pkt_cls.h:672
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81c9d0a8)
Location: include/net/pkt_cls.h:690
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
```
```
In net/sched/act_api.c (ffffffff81ca675b)
Location: include/net/pkt_cls.h:690
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init
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
In net/sched/cls_api.c (ffffffff81e59568)
Location: include/net/pkt_cls.h:715
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
```
```
In net/sched/act_api.c (ffffffff81e62c4b)
Location: include/net/pkt_cls.h:715
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init
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
In net/sched/cls_api.c (ffffffff81eb4f98)
Location: include/net/pkt_cls.h:728
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
```
```
In net/sched/act_api.c (ffffffff81ebecdb)
Location: include/net/pkt_cls.h:728
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init
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
In net/sched/cls_api.c (ffffffff81f77c58)
Location: include/net/pkt_cls.h:715
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
```
```
In net/sched/act_api.c (ffffffff81f81e59)
Location: include/net/pkt_cls.h:715
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init
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
In net/sched/cls_api.c (ffff800010c436c4)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (c0d51508)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (c000000000d3c920)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffe0007b0c28)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81935a71)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff818ef571)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff81986c01)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
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
In net/sched/cls_api.c (ffffffff819a6bc1)
Location: include/net/pkt_cls.h:605
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_setup_cb_reoffload
```
</details>
</li>
</ul>

## Differences
