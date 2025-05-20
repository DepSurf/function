# Function: <code>xfrm_policy_inexact_alloc_chain</code>

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
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197d3b0)
Location: net/xfrm/xfrm_policy.c:1106
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff8197d3b0-ffffffff8197d521: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e6800)
Location: net/xfrm/xfrm_policy.c:1110
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff819e6800-ffffffff819e6968: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1d7f0)
Location: net/xfrm/xfrm_policy.c:1112
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81a1d7f0-ffffffff81a1d958: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81b0ef70)
Location: net/xfrm/xfrm_policy.c:1115
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b0ef70-ffffffff81b0f0e6: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81b1d260)
Location: net/xfrm/xfrm_policy.c:1125
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b1d260-ffffffff81b1d3d6: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81b0ae30)
Location: net/xfrm/xfrm_policy.c:1124
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81b0ae30-ffffffff81b0afa6: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81bcdca0)
Location: net/xfrm/xfrm_policy.c:1126
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81bcdca0-ffffffff81bcde16: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81d63d40)
Location: net/xfrm/xfrm_policy.c:1126
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81d63d40-ffffffff81d63eda: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81f2ea90)
Location: net/xfrm/xfrm_policy.c:1127
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f2ea90-ffffffff81f2ec2a: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81f8e650)
Location: net/xfrm/xfrm_policy.c:1127
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81f8e650-ffffffff81f8e7ea: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff8205c360)
Location: net/xfrm/xfrm_policy.c:1142
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff8205c360-ffffffff8205c4fa: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffff800010cd9dc0)
Location: net/xfrm/xfrm_policy.c:1112
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffff800010cd9dc0-ffff800010cd9f58: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de3b3c)
Location: net/xfrm/xfrm_policy.c:1112
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
c0de3b3c-c0de3c80: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (c000000000dfad50)
Location: net/xfrm/xfrm_policy.c:1112
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
c000000000dfad50-c000000000dfaf48: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffe00082a2e0)
Location: net/xfrm/xfrm_policy.c:1112
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffe00082a2e0-ffffffe00082a426: xfrm_policy_inexact_alloc_chain.isra.0 (STB_LOCAL)
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
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bce80)
Location: net/xfrm/xfrm_policy.c:1112
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff819bce80-ffffffff819bcfe8: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81979c70)
Location: net/xfrm/xfrm_policy.c:1112
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81979c70-ffffffff81979dd8: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a27900)
Location: net/xfrm/xfrm_policy.c:1112
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81a27900-ffffffff81a27a68: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hlist_head *xfrm_policy_inexact_alloc_chain(struct xfrm_pol_inexact_bin *bin, struct xfrm_policy *policy, u8 dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a32f30)
Location: net/xfrm/xfrm_policy.c:1112
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_insert
```
**Symbols:**

```
ffffffff81a32f30-ffffffff81a33098: xfrm_policy_inexact_alloc_chain (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
