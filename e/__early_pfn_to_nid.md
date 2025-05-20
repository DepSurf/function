# Function: <code>__early_pfn_to_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181cd56)
Location: mm/page_alloc.c:4777
Inline: False
Direct callers:
  - mm/page_alloc.c:early_pfn_to_nid
  - mm/page_alloc.c:memmap_init_zone
```
**Symbols:**

```
ffffffff8181cd56-ffffffff8181cdc6: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81896fa6)
Location: mm/page_alloc.c:5318
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81896fa6-ffffffff81897010: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cb6f0)
Location: mm/page_alloc.c:5356
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff818cb6f0-ffffffff818cb75a: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81902cbf)
Location: mm/page_alloc.c:5653
Inline: True
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81902cbf-ffffffff81902d29: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198cc02)
Location: mm/page_alloc.c:5625
Inline: True
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff8198cc02-ffffffff8198cc6c: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e9490)
Location: mm/page_alloc.c:5763
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff819e9490-ffffffff819e94fa: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a24ea0)
Location: mm/page_alloc.c:6009
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81a24ea0-ffffffff81a24f0a: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a95288)
Location: mm/page_alloc.c:6195
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81a95288-ffffffff81a952f2: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81accb6b)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81accb6b-ffffffff81accbd5: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc54cf)
Location: mm/page_alloc.c:1501
Inline: False
Direct callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81bc54cf-ffffffff81bc5539: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3e470)
Location: mm/page_alloc.c:1585
Inline: True
Inline callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c306f8)
Location: mm/page_alloc.c:1620
Inline: True
Inline callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4ef21)
Location: mm/page_alloc.c:1706
Inline: True
Inline callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1edfe)
Location: mm/page_alloc.c:1689
Inline: True
Inline callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c7d57)
Location: mm/page_alloc.c:1770
Inline: True
Inline callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8214bd57)
Location: mm/mm_init.c:589
Inline: True
Inline callers:
  - mm/mm_init.c:early_pfn_to_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff8222e807)
Location: mm/mm_init.c:599
Inline: True
Inline callers:
  - mm/mm_init.c:early_pfn_to_nid
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
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9fac8)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffff800010d9fac8-ffff800010d9fb58: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eec48c)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
c000000000eec48c-c000000000eec530: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000046f32)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffe000046f32-ffffffe000046f7c: __early_pfn_to_nid (STB_GLOBAL)
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
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a6b9db)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81a6b9db-ffffffff81a6ba45: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a27f22)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81a27f22-ffffffff81a27f8c: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad7deb)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81ad7deb-ffffffff81ad7e55: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __early_pfn_to_nid(long unsigned int pfn, struct mminit_pfnnid_cache *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ae42ab)
Location: mm/page_alloc.c:6213
Inline: False
Direct callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:early_pfn_to_nid
```
**Symbols:**

```
ffffffff81ae42ab-ffffffff81ae4315: __early_pfn_to_nid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
