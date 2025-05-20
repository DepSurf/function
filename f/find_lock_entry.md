# Function: <code>find_lock_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118db50)
Location: mm/filemap.c:1089
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8118db50-ffffffff8118dbb3: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a0cc0)
Location: mm/filemap.c:1140
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811a0cc0-ffffffff811a0d69: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b08c0)
Location: mm/filemap.c:1242
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811b08c0-ffffffff811b0969: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b7ba0)
Location: mm/filemap.c:1368
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811b7ba0-ffffffff811b7c2d: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cc1d0)
Location: mm/filemap.c:1490
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811cc1d0-ffffffff811cc28d: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ed280)
Location: mm/filemap.c:1490
Inline: True
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811ed280-ffffffff811ed34f: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe750)
Location: mm/filemap.c:1528
Inline: True
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff811fe750-ffffffff811fe81f: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81215a40)
Location: mm/filemap.c:1576
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81215a40-ffffffff81215b19: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81223340)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81223340-ffffffff81223419: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81251c30)
Location: mm/filemap.c:1553
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81251c30-ffffffff81251d55: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e470)
Location: mm/filemap.c:1741
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8125e470-ffffffff8125e586: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b0c00)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffff8000102b0c00-ffff8000102b0d38: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dd55c)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
c04dd55c-c04dd68c: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000366070)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
c000000000366070-c0000000003661ec: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d658a)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffe0001d658a-ffffffe0001d665a: find_lock_entry (STB_GLOBAL)
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
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b990)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8121b990-ffffffff8121ba69: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120eb80)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff8120eb80-ffffffff8120ec59: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219730)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81219730-ffffffff81219809: find_lock_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *find_lock_entry(struct address_space *mapping, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81228830)
Location: mm/filemap.c:1579
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81228830-ffffffff812288ff: find_lock_entry (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
</ul>
</details>
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
