# Function: <code>xfrm_policy_inexact_list_reinsert</code>

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
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197cbc0)
Location: net/xfrm/xfrm_policy.c:821
Inline: False
```
**Symbols:**

```
ffffffff8197cbc0-ffffffff8197cd7b: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e5f90)
Location: net/xfrm/xfrm_policy.c:823
Inline: False
```
**Symbols:**

```
ffffffff819e5f90-ffffffff819e6136: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1cf80)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffffffff81a1cf80-ffffffff81a1d126: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0e660)
Location: net/xfrm/xfrm_policy.c:828
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
```
**Symbols:**

```
ffffffff81b0e660-ffffffff81b0e815: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1bf80)
Location: net/xfrm/xfrm_policy.c:838
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
```
**Symbols:**

```
ffffffff81b1bf80-ffffffff81b1c135: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b09c70)
Location: net/xfrm/xfrm_policy.c:837
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
```
**Symbols:**

```
ffffffff81b09c70-ffffffff81b09e25: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:839
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
```
**Symbols:**

```
ffffffff81bcd510-ffffffff81bcd6c4: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
ffffffff81d3ed44-ffffffff81d3ed59: xfrm_policy_inexact_list_reinsert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:839
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
```
**Symbols:**

```
ffffffff81d634d0-ffffffff81d636bd: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
ffffffff81f0b68d-ffffffff81f0b6a2: xfrm_policy_inexact_list_reinsert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:840
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
```
**Symbols:**

```
ffffffff81f2e180-ffffffff81f2e388: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
ffffffff820b2ecb-ffffffff820b2ee0: xfrm_policy_inexact_list_reinsert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:840
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
```
**Symbols:**

```
ffffffff81f8dd40-ffffffff81f8df48: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
ffffffff821340c9-ffffffff821340de: xfrm_policy_inexact_list_reinsert.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:855
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
```
**Symbols:**

```
ffffffff8205bac0-ffffffff8205bcce: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
ffffffff82215cd0-ffffffff82215ce4: xfrm_policy_inexact_list_reinsert.cold (STB_LOCAL)
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
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cd8ee8)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffff800010cd8ee8-ffff800010cd9090: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de32e0)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
c0de32e0-c0de3510: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfa220)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
c000000000dfa220-c000000000dfa468: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe0008293b6)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffffffe0008293b6-ffffffe00082950a: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
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
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bc610)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffffffff819bc610-ffffffff819bc7b6: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81979400)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffffffff81979400-ffffffff819795a6: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a27090)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffffffff81a27090-ffffffff81a27236: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xfrm_policy_inexact_list_reinsert(struct net *net, struct xfrm_pol_inexact_node *n, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a326c0)
Location: net/xfrm/xfrm_policy.c:825
Inline: False
```
**Symbols:**

```
ffffffff81a326c0-ffffffff81a32866: xfrm_policy_inexact_list_reinsert (STB_LOCAL)
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
