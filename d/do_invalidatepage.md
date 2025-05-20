# Function: <code>do_invalidatepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119ec10)
Location: mm/truncate.c:81
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_page
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
**Symbols:**

```
ffffffff8119ec10-ffffffff8119ec37: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b4ef2)
Location: mm/truncate.c:88
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_page
```
**Symbols:**

```
ffffffff811b4740-ffffffff811b476c: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c5515)
Location: mm/truncate.c:115
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_page
```
**Symbols:**

```
ffffffff811c4dc0-ffffffff811c4dec: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cd9d4)
Location: mm/truncate.c:113
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_page
```
**Symbols:**

```
ffffffff811cd1d0-ffffffff811cd1fc: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e2cc0)
Location: mm/truncate.c:154
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff811e2530-ffffffff811e255f: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81204277)
Location: mm/truncate.c:154
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff81203bc0-ffffffff81203bee: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81216c37)
Location: mm/truncate.c:151
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff81216580-ffffffff812165ae: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812265eb)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff81225f60-ffffffff81225f8e: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81234457)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff81233dc0-ffffffff81233dee: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261be0)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
Direct callers:
  - fs/buffer.c:block_write_full_page
```
**Symbols:**

```
ffffffff81261e40-ffffffff81261e6e: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126bef9)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff8126c140-ffffffff8126c16e: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270dfc)
Location: mm/truncate.c:146
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff81271030-ffffffff8127105e: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812add58)
Location: mm/truncate.c:146
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
Direct callers:
  - mm/readahead.c:read_cache_pages_invalidate_page
```
**Symbols:**

```
ffffffff812ae560-ffffffff812ae591: do_invalidatepage (STB_GLOBAL)
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
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4a88)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffff8000102c4450-ffff8000102c44c0: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ef348)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
Direct callers:
  - fs/buffer.c:block_write_full_page
```
**Symbols:**

```
c04eed60-c04eeda4: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037f238)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
c00000000037e910-c00000000037e974: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e5304)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffe0001e4d9c-ffffffe0001e4df0: do_invalidatepage (STB_GLOBAL)
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
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122caa7)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff8122c410-ffffffff8122c43e: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121fb87)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff8121f4f0-ffffffff8121f51e: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122a847)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff8122a1b0-ffffffff8122a1de: do_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void do_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81239c33)
Location: mm/truncate.c:152
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_cleanup_page
```
**Symbols:**

```
ffffffff812395a0-ffffffff812395ce: do_invalidatepage (STB_GLOBAL)
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
