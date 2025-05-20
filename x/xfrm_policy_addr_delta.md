# Function: <code>xfrm_policy_addr_delta</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197cb20)
Location: net/xfrm/xfrm_policy.c:785
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff8197cb20-ffffffff8197cbbe: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e5ee0)
Location: net/xfrm/xfrm_policy.c:787
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff819e5ee0-ffffffff819e5f87: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1ced0)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81a1ced0-ffffffff81a1cf77: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0e5b0)
Location: net/xfrm/xfrm_policy.c:792
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81b0e5b0-ffffffff81b0e657: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1beb0)
Location: net/xfrm/xfrm_policy.c:792
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81b1beb0-ffffffff81b1bf7d: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b09ba0)
Location: net/xfrm/xfrm_policy.c:791
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81b09ba0-ffffffff81b09c6d: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:793
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81bccb70-ffffffff81bccc44: xfrm_policy_addr_delta (STB_LOCAL)
ffffffff81d3ed25-ffffffff81d3ed44: xfrm_policy_addr_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:793
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81d62900-ffffffff81d629ee: xfrm_policy_addr_delta (STB_LOCAL)
ffffffff81f0b66e-ffffffff81f0b68d: xfrm_policy_addr_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:794
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81f2d460-ffffffff81f2d54e: xfrm_policy_addr_delta (STB_LOCAL)
ffffffff820b2eac-ffffffff820b2ecb: xfrm_policy_addr_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:794
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81f8d0d0-ffffffff81f8d213: xfrm_policy_addr_delta (STB_LOCAL)
ffffffff821340aa-ffffffff821340c9: xfrm_policy_addr_delta.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (0)
Location: net/xfrm/xfrm_policy.c:809
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_node_merge
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff8205aa60-ffffffff8205aba3: xfrm_policy_addr_delta (STB_LOCAL)
ffffffff82215cb1-ffffffff82215cd0: xfrm_policy_addr_delta.cold (STB_LOCAL)
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
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cd8b68)
Location: net/xfrm/xfrm_policy.c:789
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffff800010cd8b68-ffff800010cd8c48: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de30ac)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
c0de30ac-c0de315c: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfa0c0)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
c000000000dfa0c0-c000000000dfa214: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082908e)
Location: net/xfrm/xfrm_policy.c:789
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffe00082908e-ffffffe0008291e8: xfrm_policy_addr_delta (STB_LOCAL)
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
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bc560)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff819bc560-ffffffff819bc607: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81979350)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81979350-ffffffff819793f7: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a26fe0)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81a26fe0-ffffffff81a27087: xfrm_policy_addr_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xfrm_policy_addr_delta(const xfrm_address_t *a, const xfrm_address_t *b, u8 prefixlen, u16 family);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a32610)
Location: net/xfrm/xfrm_policy.c:789
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_lookup_inexact_addr
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_list_reinsert
```
**Symbols:**

```
ffffffff81a32610-ffffffff81a326b7: xfrm_policy_addr_delta (STB_LOCAL)
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
