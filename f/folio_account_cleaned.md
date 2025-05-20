# Function: <code>folio_account_cleaned</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void folio_account_cleaned(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81300220)
Location: mm/page-writeback.c:2559
Inline: False
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81300220-ffffffff8130035c: folio_account_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_account_cleaned(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8136ab80)
Location: mm/page-writeback.c:2697
Inline: False
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8136ab80-ffffffff8136ac70: folio_account_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_account_cleaned(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139cd10)
Location: mm/page-writeback.c:2638
Inline: False
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8139cd10-ffffffff8139ce00: folio_account_cleaned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_account_cleaned(struct folio *folio, struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c6a00)
Location: mm/page-writeback.c:2638
Inline: False
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff813c6a00-ffffffff813c6aed: folio_account_cleaned (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
