# Function: <code>folio_invalidate</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void folio_invalidate(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8130834d)
Location: mm/truncate.c:154
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813073e0-ffffffff8130741d: folio_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void folio_invalidate(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81372277)
Location: mm/truncate.c:154
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81371270-ffffffff813712ad: folio_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void folio_invalidate(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a4418)
Location: mm/truncate.c:154
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
**Symbols:**

```
ffffffff813a3440-ffffffff813a347a: folio_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void folio_invalidate(struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813cdf6b)
Location: mm/truncate.c:153
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_partial_folio
  - mm/truncate.c:truncate_cleanup_folio
```
**Symbols:**

```
ffffffff813cd0b0-ffffffff813cd0ea: folio_invalidate (STB_GLOBAL)
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
