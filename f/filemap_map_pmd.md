# Function: <code>filemap_map_pmd</code>

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
bool filemap_map_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125f990)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffff8125f990-ffffffff8125fbea: filemap_map_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool filemap_map_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129c300)
Location: mm/filemap.c:3189
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffff8129c300-ffffffff8129c55a: filemap_map_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool filemap_map_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f34a0)
Location: mm/filemap.c:3260
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffff812f34a0-ffffffff812f36e7: filemap_map_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool filemap_map_pmd(struct vm_fault *vmf, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135d7f0)
Location: mm/filemap.c:3267
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffff8135d7f0-ffffffff8135da36: filemap_map_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool filemap_map_pmd(struct vm_fault *vmf, struct folio *folio, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138f880)
Location: mm/filemap.c:3411
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffff8138f880-ffffffff8138f992: filemap_map_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool filemap_map_pmd(struct vm_fault *vmf, struct folio *folio, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b92b0)
Location: mm/filemap.c:3366
Inline: False
Direct callers:
  - mm/filemap.c:filemap_map_pages
```
**Symbols:**

```
ffffffff813b92b0-ffffffff813b93b0: filemap_map_pmd (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<code>struct folio *folio</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
