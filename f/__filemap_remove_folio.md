# Function: <code>__filemap_remove_folio</code>

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
void __filemap_remove_folio(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f4e30)
Location: mm/filemap.c:217
Inline: False
Direct callers:
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff812f4e30-ffffffff812f5088: __filemap_remove_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __filemap_remove_folio(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135ed00)
Location: mm/filemap.c:217
Inline: False
Direct callers:
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8135ed00-ffffffff8135eef6: __filemap_remove_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __filemap_remove_folio(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138fe20)
Location: mm/filemap.c:222
Inline: False
Direct callers:
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8138fe20-ffffffff81390010: __filemap_remove_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __filemap_remove_folio(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b9890)
Location: mm/filemap.c:217
Inline: False
Direct callers:
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff813b9890-ffffffff813b9a64: __filemap_remove_folio (STB_GLOBAL)
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
