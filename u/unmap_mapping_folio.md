# Function: <code>unmap_mapping_folio</code>

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
void unmap_mapping_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342da0)
Location: mm/memory.c:3514
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
```
**Symbols:**

```
ffffffff81342da0-ffffffff81342efc: unmap_mapping_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unmap_mapping_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bad60)
Location: mm/memory.c:3486
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
```
**Symbols:**

```
ffffffff813bad60-ffffffff813bae8f: unmap_mapping_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unmap_mapping_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ef880)
Location: mm/memory.c:3489
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
```
**Symbols:**

```
ffffffff813ef880-ffffffff813ef9ac: unmap_mapping_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unmap_mapping_folio(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141ad70)
Location: mm/memory.c:3568
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_folio
  - mm/memory.c:__do_fault
```
**Symbols:**

```
ffffffff8141ad70-ffffffff8141ae99: unmap_mapping_folio (STB_GLOBAL)
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
