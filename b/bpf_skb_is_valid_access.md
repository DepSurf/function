# Function: <code>bpf_skb_is_valid_access</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
bool bpf_skb_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e7b90)
Location: net/core/filter.c:3088
Inline: False
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff817e7b90-ffffffff817e7bf7: bpf_skb_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool bpf_skb_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81862ad0)
Location: net/core/filter.c:3576
Inline: False
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff81862ad0-ffffffff81862b52: bpf_skb_is_valid_access (STB_LOCAL)
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
In net/core/filter.c (ffffffff818b2880)
Location: net/core/filter.c:5075
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff818b2880-ffffffff818b28fe: bpf_skb_is_valid_access.isra.45 (STB_LOCAL)
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
In net/core/filter.c (ffffffff818d7620)
Location: net/core/filter.c:5719
Inline: True
Direct callers:
  - net/core/filter.c:flow_dissector_is_valid_access
  - net/core/filter.c:flow_dissector_is_valid_access
  - net/core/filter.c:flow_dissector_is_valid_access
  - net/core/filter.c:flow_dissector_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff818d7620-ffffffff818d76ba: bpf_skb_is_valid_access.isra.41 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81925130)
Location: net/core/filter.c:6388
Inline: True
```
**Symbols:**

```
ffffffff81925130-ffffffff819251d5: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81957560)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
ffffffff81957560-ffffffff81957605: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a2cdd4)
Location: net/core/filter.c:6688
Inline: True
Inline callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff81a2b380-ffffffff81a2b425: bpf_skb_is_valid_access.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a2e384)
Location: net/core/filter.c:7493
Inline: True
Inline callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff81a2c110-ffffffff81a2c1b5: bpf_skb_is_valid_access.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a15906)
Location: net/core/filter.c:7615
Inline: True
Inline callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff81a13620-ffffffff81a136c5: bpf_skb_is_valid_access.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81ac6b76)
Location: net/core/filter.c:7745
Inline: True
Inline callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffff81ac4ea0-ffffffff81ac4f45: bpf_skb_is_valid_access.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81c409b0)
Location: net/core/filter.c:8129
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
**Symbols:**

```
ffffffff81c409b0-ffffffff81c40b0a: bpf_skb_is_valid_access.constprop.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81df60a0)
Location: net/core/filter.c:8268
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
**Symbols:**

```
ffffffff81df60a0-ffffffff81df61fa: bpf_skb_is_valid_access.constprop.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81e68030)
Location: net/core/filter.c:8420
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
**Symbols:**

```
ffffffff81e68030-ffffffff81e68192: bpf_skb_is_valid_access.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81f27200)
Location: net/core/filter.c:8511
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:cg_skb_is_valid_access
```
**Symbols:**

```
ffffffff81f27200-ffffffff81f27362: bpf_skb_is_valid_access.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffff800010bf8ab8)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
ffff800010bf8ab8-ffff800010bf8bf8: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (c0d126d8)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
c0d126d8-c0d12840: bpf_skb_is_valid_access.part.0 (STB_LOCAL)
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
In net/core/filter.c (c000000000cdfbe0)
Location: net/core/filter.c:6475
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
c000000000cdfbe0-c000000000cdfd20: bpf_skb_is_valid_access.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffe00077a9ae)
Location: net/core/filter.c:6475
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_is_valid_access
```
**Symbols:**

```
ffffffe00077a9ae-ffffffe00077aaa0: bpf_skb_is_valid_access.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff818f7530)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
ffffffff818f7530-ffffffff818f75d5: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff818b1360)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
ffffffff818b1360-ffffffff818b1405: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81948560)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
ffffffff81948560-ffffffff81948605: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81969e70)
Location: net/core/filter.c:6475
Inline: True
```
**Symbols:**

```
ffffffff81969e70-ffffffff81969f15: bpf_skb_is_valid_access.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
