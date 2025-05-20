# Function: <code>filemap_get_read_batch</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void filemap_get_read_batch(struct address_space *mapping, long unsigned int index, long unsigned int max, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125f750)
Location: mm/filemap.c:2278
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff8125f750-ffffffff8125f98e: filemap_get_read_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void filemap_get_read_batch(struct address_space *mapping, long unsigned int index, long unsigned int max, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2332
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff8129b120-ffffffff8129b3cf: filemap_get_read_batch (STB_LOCAL)
ffffffff81cb9eec-ffffffff81cb9f0a: filemap_get_read_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void filemap_get_read_batch(struct address_space *mapping, long unsigned int index, long unsigned int max, struct folio_batch *fbatch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2376
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff812f29a0-ffffffff812f2ca2: filemap_get_read_batch (STB_LOCAL)
ffffffff81e6b4cf-ffffffff81e6b513: filemap_get_read_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void filemap_get_read_batch(struct address_space *mapping, long unsigned int index, long unsigned int max, struct folio_batch *fbatch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2373
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff8135cd70-ffffffff8135d029: filemap_get_read_batch (STB_LOCAL)
ffffffff8206213c-ffffffff82062180: filemap_get_read_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void filemap_get_read_batch(struct address_space *mapping, long unsigned int index, long unsigned int max, struct folio_batch *fbatch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2338
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff8138eda0-ffffffff8138f080: filemap_get_read_batch (STB_LOCAL)
ffffffff820e1938-ffffffff820e197f: filemap_get_read_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void filemap_get_read_batch(struct address_space *mapping, long unsigned int index, long unsigned int max, struct folio_batch *fbatch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/filemap.c (0)
Location: mm/filemap.c:2273
Inline: False
Direct callers:
  - mm/filemap.c:filemap_get_pages
  - mm/filemap.c:filemap_get_pages
```
**Symbols:**

```
ffffffff813b8450-ffffffff813b872d: filemap_get_read_batch (STB_LOCAL)
ffffffff821be347-ffffffff821be38e: filemap_get_read_batch.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
