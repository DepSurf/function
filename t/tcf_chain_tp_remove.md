# Function: <code>tcf_chain_tp_remove</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81803015)
Location: net/sched/cls_api.c:380
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcf_chain_tp_remove(struct tcf_chain *chain, struct tcf_chain_info *chain_info, struct tcf_proto *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f5e0)
Location: net/sched/cls_api.c:556
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff8187f5e0-ffffffff8187f630: tcf_chain_tp_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2c40)
Location: net/sched/cls_api.c:902
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff818d2c40-ffffffff818d2cb8: tcf_chain_tp_remove.isra.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818feef0)
Location: net/sched/cls_api.c:1348
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff818feef0-ffffffff818fef62: tcf_chain_tp_remove.isra.41 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff819619eb)
Location: net/sched/cls_api.c:1713
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81998a38)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81a703e5)
Location: net/sched/cls_api.c:1664
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81a78ddb)
Location: net/sched/cls_api.c:1666
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81a61cae)
Location: net/sched/cls_api.c:1667
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81b1aece)
Location: net/sched/cls_api.c:1665
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81ca3c6b)
Location: net/sched/cls_api.c:1684
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81e5f5cc)
Location: net/sched/cls_api.c:1686
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81ebacb8)
Location: net/sched/cls_api.c:1834
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81f7dea8)
Location: net/sched/cls_api.c:1884
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffff800010c458b0)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (c0d5742c)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (c000000000d42a9c)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffe0007b465c)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff819388a8)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff818f23a8)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81989a38)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff819acdf8)
Location: net/sched/cls_api.c:1651
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
