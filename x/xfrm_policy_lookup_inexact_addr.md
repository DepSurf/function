# Function: <code>xfrm_policy_lookup_inexact_addr</code>

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
In net/xfrm/xfrm_policy.c (ffffffff8197ce55)
Location: net/xfrm/xfrm_policy.c:1902
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff8197cd80-ffffffff8197ce00: xfrm_policy_lookup_inexact_addr.part.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e6140)
Location: net/xfrm/xfrm_policy.c:1908
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff819e6140-ffffffff819e61c6: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1d130)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81a1d130-ffffffff81a1d1b6: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0e820)
Location: net/xfrm/xfrm_policy.c:1901
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81b0e820-ffffffff81b0e8a9: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1c300)
Location: net/xfrm/xfrm_policy.c:1911
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81b1c300-ffffffff81b1c385: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b09ff0)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81b09ff0-ffffffff81b0a075: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bcce10)
Location: net/xfrm/xfrm_policy.c:1911
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81bcce10-ffffffff81bcce95: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d62bf0)
Location: net/xfrm/xfrm_policy.c:1911
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81d62bf0-ffffffff81d62c81: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2d790)
Location: net/xfrm/xfrm_policy.c:1982
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81f2d790-ffffffff81f2d821: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8d460)
Location: net/xfrm/xfrm_policy.c:1984
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81f8d460-ffffffff81f8d4f1: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_spinlock_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205adf0)
Location: net/xfrm/xfrm_policy.c:2004
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff8205adf0-ffffffff8205ae81: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
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
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cd9090)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffff800010cd9090-ffff800010cd9138: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de315c)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
c0de315c-c0de321c: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfa470)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
c000000000dfa470-c000000000dfa56c: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082950a)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
```
**Symbols:**

```
ffffffe00082950a-ffffffe000829596: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
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
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bc7c0)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff819bc7c0-ffffffff819bc846: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819795b0)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff819795b0-ffffffff81979636: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a27240)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81a27240-ffffffff81a272c6: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xfrm_pol_inexact_node *xfrm_policy_lookup_inexact_addr(const struct rb_root *r, seqcount_t *count, const xfrm_address_t *addr, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a32870)
Location: net/xfrm/xfrm_policy.c:1910
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
  - net/xfrm/xfrm_policy.c:xfrm_policy_find_inexact_candidates
```
**Symbols:**

```
ffffffff81a32870-ffffffff81a328f6: xfrm_policy_lookup_inexact_addr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>seqcount_t *count</code> ➡️ <code>seqcount_spinlock_t *count</code>
</li>
</ul>
</details>
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
