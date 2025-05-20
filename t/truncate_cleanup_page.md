# Function: <code>truncate_cleanup_page</code>

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
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e1b70)
Location: mm/truncate.c:179
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff811e1b70-ffffffff811e1c3b: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81203250)
Location: mm/truncate.c:179
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81203250-ffffffff8120330a: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81215bf0)
Location: mm/truncate.c:176
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81215bf0-ffffffff81215caa: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81225600)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81225600-ffffffff812256c0: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81233450)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81233450-ffffffff81233510: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81260c50)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81260c50-ffffffff81260d1a: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126b030)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff8126b030-ffffffff8126b116: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void truncate_cleanup_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270170)
Location: mm/truncate.c:170
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81270170-ffffffff81270222: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void truncate_cleanup_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ad400)
Location: mm/truncate.c:170
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff812ad400-ffffffff812ad4b5: truncate_cleanup_page (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c39d8)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffff8000102c39d8-ffff8000102c3ac8: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ee510)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
c04ee510-c04ee5dc: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037de00)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
c00000000037de00-c00000000037df88: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e45d0)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffe0001e45d0-ffffffe0001e4680: truncate_cleanup_page (STB_LOCAL)
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
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122baa0)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff8122baa0-ffffffff8122bb60: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121eb90)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff8121eb90-ffffffff8121ec50: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81229840)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81229840-ffffffff81229900: truncate_cleanup_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void truncate_cleanup_page(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81238c50)
Location: mm/truncate.c:177
Inline: False
Direct callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:generic_error_remove_page
```
**Symbols:**

```
ffffffff81238c50-ffffffff81238d10: truncate_cleanup_page (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, page</code> ➡️ <code>page</code>
</li>
</ul>
</details>
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
