# Function: <code>tc_indr_block_call</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ff120)
Location: net/sched/cls_api.c:583
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818ff120-ffffffff818ff1c2: tc_indr_block_call.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195f940)
Location: net/sched/cls_api.c:769
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff8195f940-ffffffff8195fa25: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81996750)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81996750-ffffffff819967ef: tc_indr_block_call.isra.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffff800010c43078)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffff800010c43078-ffff800010c43134: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tc_indr_block_call(struct tcf_block *block, struct net_device *dev, struct tcf_block_ext_info *ei, enum flow_block_command command, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d5463c)
Location: net/sched/cls_api.c:680
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
c0d5463c-c0d546f8: tc_indr_block_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (c000000000d3ecb0)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
c000000000d3ecb0-c000000000d3ed7c: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1f86)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffe0007b1f86-ffffffe0007b2016: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819365c0)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff819365c0-ffffffff8193665f: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f00c0)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818f00c0-ffffffff818f015f: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81987750)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81987750-ffffffff819877ef: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a9c10)
Location: net/sched/cls_api.c:680
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff819a9c10-ffffffff819a9caf: tc_indr_block_call.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
