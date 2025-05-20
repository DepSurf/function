# Function: <code>tc_chain_tmplt_add</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819000d3)
Location: net/sched/cls_api.c:2103
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81960bcb)
Location: net/sched/cls_api.c:2747
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81997cab)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_chain_tmplt_add(struct tcf_chain *chain, struct net *net, struct nlattr **tca, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c950)
Location: net/sched/cls_api.c:2747
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
**Symbols:**

```
ffffffff81a6c950-ffffffff81a6ca80: tc_chain_tmplt_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_chain_tmplt_add(struct tcf_chain *chain, struct net *net, struct nlattr **tca, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75300)
Location: net/sched/cls_api.c:2748
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
**Symbols:**

```
ffffffff81a75300-ffffffff81a7542f: tc_chain_tmplt_add (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a632dd)
Location: net/sched/cls_api.c:2749
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81b1c657)
Location: net/sched/cls_api.c:2747
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81ca1fac)
Location: net/sched/cls_api.c:2766
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81e5e826)
Location: net/sched/cls_api.c:2770
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81ebc31b)
Location: net/sched/cls_api.c:2933
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81f7f516)
Location: net/sched/cls_api.c:2989
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffff800010c44d44)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (c0d567b4)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (c000000000d419f0)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffe0007b3c2e)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81937b1b)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff818f161b)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81988cab)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff819abfab)
Location: net/sched/cls_api.c:2711
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
