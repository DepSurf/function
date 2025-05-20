# Function: <code>__xfrm_policy_inexact_prune_bin</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197fb70)
Location: net/xfrm/xfrm_policy.c:1066
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff8197fb70-ffffffff8197fd37: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e9840)
Location: net/xfrm/xfrm_policy.c:1070
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff819e9840-ffffffff819e9a76: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a20870)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff81a20870-ffffffff81a20a50: __xfrm_policy_inexact_prune_bin.part.0 (STB_LOCAL)
ffffffff81a20a50-ffffffff81a20ac6: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b13200)
Location: net/xfrm/xfrm_policy.c:1075
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b13200-ffffffff81b1332d: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b21610)
Location: net/xfrm/xfrm_policy.c:1085
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b21610-ffffffff81b2174b: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0f230)
Location: net/xfrm/xfrm_policy.c:1084
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b0f230-ffffffff81b0f36b: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd2640)
Location: net/xfrm/xfrm_policy.c:1086
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81bd2640-ffffffff81bd277b: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d68360)
Location: net/xfrm/xfrm_policy.c:1086
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81d68360-ffffffff81d68453: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f333f0)
Location: net/xfrm/xfrm_policy.c:1087
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f333f0-ffffffff81f334e3: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f92770)
Location: net/xfrm/xfrm_policy.c:1087
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f92770-ffffffff81f92861: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff820604e0)
Location: net/xfrm/xfrm_policy.c:1102
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_dev_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_flush
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff820604e0-ffffffff820605d1: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdcc80)
Location: net/xfrm/xfrm_policy.c:1072
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffff800010cdcc80-ffff800010cdcf84: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de6bdc)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
c0de6bdc-c0de6f24: __xfrm_policy_inexact_prune_bin.part.0 (STB_LOCAL)
c0de6f24-c0de6fe0: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfc590)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
c000000000dfc590-c000000000dfc928: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082a9f2)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffe00082a9f2-ffffffe00082ac36: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bff00)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff819bff00-ffffffff819c00e0: __xfrm_policy_inexact_prune_bin.part.0 (STB_LOCAL)
ffffffff819c00e0-ffffffff819c0156: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197ccf0)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff8197ccf0-ffffffff8197ced0: __xfrm_policy_inexact_prune_bin.part.0 (STB_LOCAL)
ffffffff8197ced0-ffffffff8197cf46: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2a980)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff81a2a980-ffffffff81a2ab60: __xfrm_policy_inexact_prune_bin.part.0 (STB_LOCAL)
ffffffff81a2ab60-ffffffff81a2abd6: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_policy_inexact_prune_bin(struct xfrm_pol_inexact_bin *b, bool net_exit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a35f20)
Location: net/xfrm/xfrm_policy.c:1072
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_fini
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_flush
```
**Symbols:**

```
ffffffff81a35f20-ffffffff81a36169: __xfrm_policy_inexact_prune_bin.part.0 (STB_LOCAL)
ffffffff81a36170-ffffffff81a361e6: __xfrm_policy_inexact_prune_bin (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
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
