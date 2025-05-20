# Function: <code>tc_dev_block</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819936e0)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff819936e0-ffffffff81993750: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fb08)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffff800010c3fb08-ffff800010c3fb9c: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d516f4)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
c0d516f4-c0d517ac: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a390)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
c000000000d3a390-c000000000d3a474: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007af644)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffe0007af644-ffffffe0007af6cc: tc_dev_block (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933550)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff81933550-ffffffff819335c0: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed050)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff818ed050-ffffffff818ed0c0: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819846e0)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff819846e0-ffffffff81984750: tc_dev_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_block *tc_dev_block(struct net_device *dev, bool ingress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a6d50)
Location: net/sched/cls_api.c:634
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
  - net/sched/cls_api.c:tc_indr_block_get_and_cmd
```
**Symbols:**

```
ffffffff819a6d50-ffffffff819a6dc0: tc_dev_block (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
