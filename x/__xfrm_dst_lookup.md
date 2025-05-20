# Function: <code>__xfrm_dst_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b28bf)
Location: net/xfrm/xfrm_policy.c:118
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8181f9bf)
Location: net/xfrm/xfrm_policy.c:118
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8185121f)
Location: net/xfrm/xfrm_policy.c:124
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81875e6a)
Location: net/xfrm/xfrm_policy.c:119
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81873310-ffffffff81873340: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f6f6d)
Location: net/xfrm/xfrm_policy.c:122
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff818f3d20-ffffffff818f3d59: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194cfc2)
Location: net/xfrm/xfrm_policy.c:122
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff8194a120-ffffffff8194a158: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197e8ac)
Location: net/xfrm/xfrm_policy.c:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff8197be10-ffffffff8197be48: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e78b9)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff819e5900-ffffffff819e5940: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1e8a9)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81a1c930-ffffffff81a1c970: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11410)
Location: net/xfrm/xfrm_policy.c:253
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81b0dca0-ffffffff81b0dce0: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1db60)
Location: net/xfrm/xfrm_policy.c:253
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81b1db60-ffffffff81b1dbbf: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0b500)
Location: net/xfrm/xfrm_policy.c:252
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81b0b500-ffffffff81b0b55f: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bce3d0)
Location: net/xfrm/xfrm_policy.c:254
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81bce3d0-ffffffff81bce47c: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d66c29)
Location: net/xfrm/xfrm_policy.c:254
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81d64390-ffffffff81d6444c: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2f979)
Location: net/xfrm/xfrm_policy.c:254
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_lookup
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81f2f140-ffffffff81f2f1fc: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f90409)
Location: net/xfrm/xfrm_policy.c:254
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_lookup
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81f8f930-ffffffff81f8f9f6: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205e169)
Location: net/xfrm/xfrm_policy.c:269
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_lookup
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff8205d690-ffffffff8205d756: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cdacbc)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffff800010cd8c48-ffff800010cd8d04: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de4b3c)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
c0de2804-c0de287c: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dffc34)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
c000000000df9420-c000000000df94a8: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082c84e)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffe0008291e8-ffffffe000829268: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bdf39)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff819bbfc0-ffffffff819bc000: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197ad29)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81978db0-ffffffff81978df0: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a289b9)
Location: net/xfrm/xfrm_policy.c:250
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81a26a40-ffffffff81a26a80: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *__xfrm_dst_lookup(struct net *net, int tos, int oif, const xfrm_address_t *saddr, const xfrm_address_t *daddr, int family, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a321a0)
Location: net/xfrm/xfrm_policy.c:250
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_state_add
```
**Symbols:**

```
ffffffff81a321a0-ffffffff81a32231: __xfrm_dst_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 mark</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
