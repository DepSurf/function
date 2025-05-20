# Function: <code>xfrm_pol_bin_key</code>

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
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197bf40)
Location: net/xfrm/xfrm_policy.c:1440
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff8197bf40-ffffffff8197bfa1: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819e5420)
Location: net/xfrm/xfrm_policy.c:1446
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff819e5420-ffffffff819e547c: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a1c450)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff81a1c450-ffffffff81a1c4af: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0f680)
Location: net/xfrm/xfrm_policy.c:1442
Inline: True
```
**Symbols:**

```
ffffffff81b0f680-ffffffff81b0f6df: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b1d970)
Location: net/xfrm/xfrm_policy.c:1452
Inline: True
```
**Symbols:**

```
ffffffff81b1d970-ffffffff81b1d9cf: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b0b1c0)
Location: net/xfrm/xfrm_policy.c:1451
Inline: True
```
**Symbols:**

```
ffffffff81b0b1c0-ffffffff81b0b21f: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bce090)
Location: net/xfrm/xfrm_policy.c:1453
Inline: True
```
**Symbols:**

```
ffffffff81bce090-ffffffff81bce0ef: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d64160)
Location: net/xfrm/xfrm_policy.c:1453
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff81d64160-ffffffff81d641cb: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2eee0)
Location: net/xfrm/xfrm_policy.c:1454
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff81f2eee0-ffffffff81f2ef4b: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8f420)
Location: net/xfrm/xfrm_policy.c:1454
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff81f8f420-ffffffff81f8f48b: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205d010)
Location: net/xfrm/xfrm_policy.c:1470
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_lookup
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff8205d010-ffffffff8205d07b: xfrm_pol_bin_key (STB_LOCAL)
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
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010cda638)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffff800010cda638-ffff800010cda6d8: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de2258)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
c0de2258-c0de22d0: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000df8df0)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
c000000000df8df0-c000000000df8e78: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082b2c4)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffe00082b2c4-ffffffe00082b372: xfrm_pol_bin_key (STB_LOCAL)
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
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819bbae0)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff819bbae0-ffffffff819bbb3f: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819788d0)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff819788d0-ffffffff8197892f: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a26560)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff81a26560-ffffffff81a265bf: xfrm_pol_bin_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 xfrm_pol_bin_key(const void *data, u32 len, u32 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a31a10)
Location: net/xfrm/xfrm_policy.c:1448
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_bysel_ctx
  - net/xfrm/xfrm_policy.c:xfrm_pol_bin_obj
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
**Symbols:**

```
ffffffff81a31a10-ffffffff81a31a6f: xfrm_pol_bin_key (STB_LOCAL)
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
