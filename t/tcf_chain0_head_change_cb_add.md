# Function: <code>tcf_chain0_head_change_cb_add</code>

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
In net/sched/cls_api.c (ffffffff818ff4b1)
Location: net/sched/cls_api.c:683
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
In net/sched/cls_api.c (ffffffff8195fca2)
Location: net/sched/cls_api.c:883
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
In net/sched/cls_api.c (ffffffff81996d0e)
Location: net/sched/cls_api.c:795
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
int tcf_chain0_head_change_cb_add(struct tcf_block *block, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e080)
Location: net/sched/cls_api.c:758
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a6e080-ffffffff81a6e1a9: tcf_chain0_head_change_cb_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_chain0_head_change_cb_add(struct tcf_block *block, struct tcf_block_ext_info *ei, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a76a50)
Location: net/sched/cls_api.c:760
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a76a50-ffffffff81a76b79: tcf_chain0_head_change_cb_add (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a636ae)
Location: net/sched/cls_api.c:760
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
In net/sched/cls_api.c (ffffffff81b1ca2e)
Location: net/sched/cls_api.c:761
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
In net/sched/cls_api.c (ffffffff81ca0c4e)
Location: net/sched/cls_api.c:778
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
In net/sched/cls_api.c (ffffffff81e5cc8e)
Location: net/sched/cls_api.c:780
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
In net/sched/cls_api.c (ffffffff81eb983e)
Location: net/sched/cls_api.c:885
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
In net/sched/cls_api.c (ffffffff81f7c9d2)
Location: net/sched/cls_api.c:885
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
In net/sched/cls_api.c (ffff800010c43df0)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (c0d549cc)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (c000000000d3f2a0)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (ffffffe0007b22ae)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (ffffffff81936b7e)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (ffffffff818f067e)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (ffffffff81987d0e)
Location: net/sched/cls_api.c:795
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
In net/sched/cls_api.c (ffffffff819a9f6e)
Location: net/sched/cls_api.c:795
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
