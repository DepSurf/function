# Function: <code>mm_account_pinned_pages</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818337a3)
Location: net/core/skbuff.c:893
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81831150-ffffffff818311d4: mm_account_pinned_pages.part.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187b5d0)
Location: net/core/skbuff.c:895
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff8187b5d0-ffffffff8187b682: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c410)
Location: net/core/skbuff.c:897
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff8189c410-ffffffff8189c4c8: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6c90)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff818e6c90-ffffffff818e6d48: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919070)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81919070-ffffffff81919128: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819edf59)
Location: net/core/skbuff.c:1054
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff819eccf0-ffffffff819ecdb7: mm_account_pinned_pages.part.0 (STB_LOCAL)
ffffffff819ecdc0-ffffffff819ecdff: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819edbf9)
Location: net/core/skbuff.c:1065
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff819ec9b0-ffffffff819eca77: mm_account_pinned_pages.part.0 (STB_LOCAL)
ffffffff819eca80-ffffffff819ecabf: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819d5ad9)
Location: net/core/skbuff.c:1108
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
```
**Symbols:**

```
ffffffff819d2e90-ffffffff819d2f57: mm_account_pinned_pages.part.0 (STB_LOCAL)
ffffffff819d2f60-ffffffff819d2f9f: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81a85709)
Location: net/core/skbuff.c:1129
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_alloc
```
**Symbols:**

```
ffffffff81a82b70-ffffffff81a82c37: mm_account_pinned_pages.part.0 (STB_LOCAL)
ffffffff81a82c40-ffffffff81a82c7f: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf7870)
Location: net/core/skbuff.c:1131
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81bf7870-ffffffff81bf7966: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da65e0)
Location: net/core/skbuff.c:1312
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81da65e0-ffffffff81da66bf: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e156e0)
Location: net/core/skbuff.c:1452
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81e156e0-ffffffff81e157d4: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed2a80)
Location: net/core/skbuff.c:1540
Inline: False
Direct callers:
  - net/core/skbuff.c:msg_zerocopy_realloc
  - net/core/skbuff.c:msg_zerocopy_realloc
```
**Symbols:**

```
ffffffff81ed2a80-ffffffff81ed2b74: mm_account_pinned_pages (STB_GLOBAL)
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
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb2cd0)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffff800010bb2cd0-ffff800010bb2de0: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf86c)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
c0ccf86c-c0ccf95c: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89b60)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
c000000000c89b60-c000000000c89cc0: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007437fe)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffe0007437fe-ffffffe0007438bc: mm_account_pinned_pages (STB_GLOBAL)
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
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9070)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff818b9070-ffffffff818b9128: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81872fc0)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff81872fc0-ffffffff81873078: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190a070)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff8190a070-ffffffff8190a128: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mm_account_pinned_pages(struct mmpin *mmp, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192b170)
Location: net/core/skbuff.c:1055
Inline: True
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_realloc
  - net/core/skbuff.c:sock_zerocopy_alloc
```
**Symbols:**

```
ffffffff8192b170-ffffffff8192b228: mm_account_pinned_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
