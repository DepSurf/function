# Function: <code>tcf_block_offload_cmd</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f7f6)
Location: net/sched/cls_api.c:256
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_put_ext
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff818d4bb1)
Location: net/sched/cls_api.c:277
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
In net/sched/cls_api.c (ffffffff818ff545)
Location: net/sched/cls_api.c:613
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_get_ext
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
In net/sched/cls_api.c (ffffffff8195f150)
Location: net/sched/cls_api.c:804
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff8195f150-ffffffff8195f204: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81996520)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81996520-ffffffff819965d4: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6eee0)
Location: net/sched/cls_api.c:667
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81a6eee0-ffffffff81a6efe1: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a778b0)
Location: net/sched/cls_api.c:669
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81a778b0-ffffffff81a779b9: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5fed0)
Location: net/sched/cls_api.c:669
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81a5fed0-ffffffff81a5ffed: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b190f0)
Location: net/sched/cls_api.c:670
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81b190f0-ffffffff81b19263: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca07f0)
Location: net/sched/cls_api.c:687
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81ca07f0-ffffffff81ca0977: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5c800)
Location: net/sched/cls_api.c:689
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81e5c800-ffffffff81e5c987: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb93c0)
Location: net/sched/cls_api.c:794
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81eb93c0-ffffffff81eb9537: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7c510)
Location: net/sched/cls_api.c:794
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffff81f7c510-ffffffff81f7c687: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
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
In net/sched/cls_api.c (ffff800010c42e08)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffff800010c42e08-ffff800010c42ed4: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_block_offload_cmd(struct tcf_block *block, struct net_device *dev, struct tcf_block_ext_info *ei, enum flow_block_command command, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d543dc)
Location: net/sched/cls_api.c:705
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
c0d543dc-c0d544a8: tcf_block_offload_cmd (STB_LOCAL)
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
In net/sched/cls_api.c (c000000000d3e9a0)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
c000000000d3e9a0-c000000000d3ea80: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffe0007b1da6)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_offload_unbind
```
**Symbols:**

```
ffffffe0007b1da6-ffffffe0007b1e3e: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81936390)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81936390-ffffffff81936444: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff818efe90)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff818efe90-ffffffff818eff44: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81987520)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff81987520-ffffffff819875d4: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff819a99e0)
Location: net/sched/cls_api.c:705
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_block_get_ext
```
**Symbols:**

```
ffffffff819a99e0-ffffffff819a9a94: tcf_block_offload_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
