# Function: <code>truncate_cleanup_folio</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void truncate_cleanup_folio(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:173
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
```
**Symbols:**

```
ffffffff81307b90-ffffffff81307c68: truncate_cleanup_folio (STB_LOCAL)
ffffffff81e6bdfb-ffffffff81e6be15: truncate_cleanup_folio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void truncate_cleanup_folio(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:173
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
```
**Symbols:**

```
ffffffff81371db0-ffffffff81371e77: truncate_cleanup_folio (STB_LOCAL)
ffffffff82062780-ffffffff8206279a: truncate_cleanup_folio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void truncate_cleanup_folio(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:173
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_partial_folio
```
**Symbols:**

```
ffffffff813a3f60-ffffffff813a4016: truncate_cleanup_folio (STB_LOCAL)
ffffffff820e1f25-ffffffff820e1f40: truncate_cleanup_folio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void truncate_cleanup_folio(struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:172
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_folio
  - mm/truncate.c:truncate_inode_partial_folio
```
**Symbols:**

```
ffffffff813cdae0-ffffffff813cdb9e: truncate_cleanup_folio (STB_LOCAL)
ffffffff821be941-ffffffff821be959: truncate_cleanup_folio.cold (STB_LOCAL)
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
