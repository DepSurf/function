# Function: <code>filemap_get_pages</code>

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
int filemap_get_pages(struct kiocb *iocb, struct iov_iter *iter, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261fd0)
Location: mm/filemap.c:2447
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
```
**Symbols:**

```
ffffffff81261fd0-ffffffff81262374: filemap_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filemap_get_pages(struct kiocb *iocb, struct iov_iter *iter, struct pagevec *pvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129e5a0)
Location: mm/filemap.c:2528
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
```
**Symbols:**

```
ffffffff8129e5a0-ffffffff8129e97e: filemap_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filemap_get_pages(struct kiocb *iocb, struct iov_iter *iter, struct folio_batch *fbatch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f2cb0)
Location: mm/filemap.c:2574
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
```
**Symbols:**

```
ffffffff812f2cb0-ffffffff812f2ff4: filemap_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_get_pages(struct kiocb *iocb, struct iov_iter *iter, struct folio_batch *fbatch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135d040)
Location: mm/filemap.c:2580
Inline: False
Direct callers:
  - mm/filemap.c:filemap_read
```
**Symbols:**

```
ffffffff8135d040-ffffffff8135d3ba: filemap_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_get_pages(struct kiocb *iocb, size_t count, struct folio_batch *fbatch, bool need_uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138f090)
Location: mm/filemap.c:2544
Inline: False
Direct callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
```
**Symbols:**

```
ffffffff8138f090-ffffffff8138f439: filemap_get_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_get_pages(struct kiocb *iocb, size_t count, struct folio_batch *fbatch, bool need_uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b8740)
Location: mm/filemap.c:2479
Inline: False
Direct callers:
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
```
**Symbols:**

```
ffffffff813b8740-ffffffff813b8ae9: filemap_get_pages (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param added. </b>
<code>bool need_uptodate</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iov_iter *iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
