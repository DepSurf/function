# Function: <code>lru_cache_add_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dcc0)
Location: mm/swap.c:653
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8119dcc0-ffffffff8119dcdb: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2f30)
Location: mm/swap.c:412
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811b2f30-ffffffff811b2f69: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c35a0)
Location: mm/swap.c:413
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811c35a0-ffffffff811c35d9: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:424
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811cc130-ffffffff811cc140: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:424
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811e1120-ffffffff811e1130: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:425
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff812029a0-ffffffff812029b0: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:419
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81215320-ffffffff81215330: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812242a0)
Location: mm/swap.c:420
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812242a0-ffffffff812242d9: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232030)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81232030-ffffffff81232069: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffff8000102c2a20-ffff8000102c2a48: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c04edbe0-c04edc00: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037bd30)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c00000000037bd30-c00000000037bda8: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffe0001e3d6e-ffffffe0001e3d96: lru_cache_add_file (STB_GLOBAL)
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
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122a680)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8122a680-ffffffff8122a6b9: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121d7a0)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8121d7a0-ffffffff8121d7d9: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228420)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81228420-ffffffff81228459: lru_cache_add_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lru_cache_add_file(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81237770)
Location: mm/swap.c:421
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_file
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81237770-ffffffff812377a9: lru_cache_add_file (STB_GLOBAL)
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
