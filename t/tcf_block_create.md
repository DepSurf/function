# Function: <code>tcf_block_create</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d4c14)
Location: net/sched/cls_api.c:395
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff818ff5af)
Location: net/sched/cls_api.c:756
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff8195fd71)
Location: net/sched/cls_api.c:982
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81996de0)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_block *tcf_block_create(struct net *net, struct Qdisc *q, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6c5d0)
Location: net/sched/cls_api.c:857
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a6c5d0-ffffffff81a6c6f4: tcf_block_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_block *tcf_block_create(struct net *net, struct Qdisc *q, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74e90)
Location: net/sched/cls_api.c:859
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a74e90-ffffffff81a74fb4: tcf_block_create (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a63806)
Location: net/sched/cls_api.c:859
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81b1cb86)
Location: net/sched/cls_api.c:860
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81ca0da9)
Location: net/sched/cls_api.c:877
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81e5cde9)
Location: net/sched/cls_api.c:879
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81eb9991)
Location: net/sched/cls_api.c:984
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81f7cb59)
Location: net/sched/cls_api.c:984
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffff800010c43e98)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (c0d54b2c)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (c000000000d3f154)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffe0007b2364)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81936c50)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff818f0750)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff81987de0)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff819aa040)
Location: net/sched/cls_api.c:894
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
