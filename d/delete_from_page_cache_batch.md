# Function: <code>delete_from_page_cache_batch</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd4d0)
Location: mm/filemap.c:369
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff811cd4d0-ffffffff811cd799: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef020)
Location: mm/filemap.c:369
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff811ef020-ffffffff811ef2cc: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812007d0)
Location: mm/filemap.c:335
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff812007d0-ffffffff81200ac5: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81218400)
Location: mm/filemap.c:337
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff81218400-ffffffff812186e9: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81225c90)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff81225c90-ffffffff81225f5a: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81250fa0)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff81250fa0-ffffffff8125109a: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c650)
Location: mm/filemap.c:343
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8125c650-ffffffff8125c728: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261430)
Location: mm/filemap.c:334
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff81261430-ffffffff81261508: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129e090)
Location: mm/filemap.c:335
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8129e090-ffffffff8129e161: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f5200)
Location: mm/filemap.c:318
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff812f5200-ffffffff812f558a: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f070)
Location: mm/filemap.c:318
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8135f070-ffffffff8135f3c7: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81390180)
Location: mm/filemap.c:323
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff81390180-ffffffff8139052b: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct folio_batch *fbatch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b9bc0)
Location: mm/filemap.c:318
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff813b9bc0-ffffffff813b9f68: delete_from_page_cache_batch (STB_GLOBAL)
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
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b2db8)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffff8000102b2db8-ffff8000102b3138: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dffc4)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
c04dffc4-c04e0388: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369880)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
c000000000369880-c000000000369c84: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8634)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffe0001d8634-ffffffe0001d88ce: delete_from_page_cache_batch (STB_GLOBAL)
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
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e2e0)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8121e2e0-ffffffff8121e5aa: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812114a0)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff812114a0-ffffffff8121176a: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c080)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8121c080-ffffffff8121c34a: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void delete_from_page_cache_batch(struct address_space *mapping, struct pagevec *pvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b0f0)
Location: mm/filemap.c:342
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8122b0f0-ffffffff8122b3df: delete_from_page_cache_batch (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio_batch *fbatch</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pagevec *pvec</code>
</li>
</ul>
</details>
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
