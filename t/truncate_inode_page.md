# Function: <code>truncate_inode_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119ec40)
Location: mm/truncate.c:149
Inline: False
Direct callers:
  - mm/truncate.c:generic_error_remove_page
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8119ec40-ffffffff8119ecc2: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b4770)
Location: mm/truncate.c:156
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811b4770-ffffffff811b482d: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c4df0)
Location: mm/truncate.c:183
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811c4df0-ffffffff811c4ead: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cd200)
Location: mm/truncate.c:181
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811cd200-ffffffff811cd2bc: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e1c5f)
Location: mm/truncate.c:226
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff811e2560-ffffffff811e2591: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8120332f)
Location: mm/truncate.c:222
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81203bf0-ffffffff81203c1b: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81215ccf)
Location: mm/truncate.c:219
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812165b0-ffffffff812165db: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812256e3)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81225f90-ffffffff81225fbd: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81233533)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81233df0-ffffffff81233e1d: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812617c0)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81261e70-ffffffff81261e9f: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126bbee)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8126c170-ffffffff8126c19f: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270b2f)
Location: mm/truncate.c:211
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff81271060-ffffffff81271092: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ada79)
Location: mm/truncate.c:211
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812ae5a0-ffffffff812ae5d2: truncate_inode_page (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c3afc)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffff8000102c44c0-ffff8000102c4510: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ee610)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c04eeda4-c04eede4: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037dfd4)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
c00000000037e980-c00000000037e9e8: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e46ac)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffe0001e4df0-ffffffe0001e4e36: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122bb83)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8122c440-ffffffff8122c46d: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121ec73)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8121f520-ffffffff8121f54d: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81229923)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff8122a1e0-ffffffff8122a20d: truncate_inode_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int truncate_inode_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81238d33)
Location: mm/truncate.c:220
Inline: True
Inline callers:
  - mm/truncate.c:generic_error_remove_page
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
**Symbols:**

```
ffffffff812395d0-ffffffff812395fd: truncate_inode_page (STB_GLOBAL)
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
