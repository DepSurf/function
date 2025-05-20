# Function: <code>__set_page_dirty_nobuffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119a990)
Location: mm/page-writeback.c:2459
Inline: False
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff8119a990-ffffffff8119aaca: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811af2a0)
Location: mm/page-writeback.c:2505
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff811af2a0-ffffffff811af3e5: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bf940)
Location: mm/page-writeback.c:2472
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff811bf940-ffffffff811bfaa2: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c7b10)
Location: mm/page-writeback.c:2475
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff811c7b10-ffffffff811c7c6a: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc950)
Location: mm/page-writeback.c:2458
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff811dc950-ffffffff811dcaaa: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fc9f0)
Location: mm/page-writeback.c:2459
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff811fc9f0-ffffffff811fcb3e: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120f540)
Location: mm/page-writeback.c:2453
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff8120f540-ffffffff8120f68e: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81221540)
Location: mm/page-writeback.c:2461
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff81221540-ffffffff812216a2: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122eff0)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff8122eff0-ffffffff8122f152: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff8125c0b0)
Location: mm/page-writeback.c:2475
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff8125c0b0-ffffffff8125c1c8: __set_page_dirty_nobuffers.part.0 (STB_LOCAL)
ffffffff8125c1d0-ffffffff8125c216: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page-writeback.c (ffffffff81266480)
Location: mm/page-writeback.c:2473
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff81266480-ffffffff81266598: __set_page_dirty_nobuffers.part.0 (STB_LOCAL)
ffffffff812665a0-ffffffff812665e6: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8126af90)
Location: mm/page-writeback.c:2473
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff8126af90-ffffffff8126b0e7: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a7f00)
Location: mm/page-writeback.c:2519
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff812a7f00-ffffffff812a7fb0: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff81301040)
Location: mm/folio-compat.c:88
Inline: False
```
**Symbols:**

```
ffffffff81301040-ffffffff813010d9: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8136b890)
Location: mm/folio-compat.c:60
Inline: False
```
**Symbols:**

```
ffffffff8136b890-ffffffff8136b929: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff8139dac0)
Location: mm/folio-compat.c:61
Inline: False
```
**Symbols:**

```
ffffffff8139dac0-ffffffff8139db65: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813c7830)
Location: mm/folio-compat.c:61
Inline: False
```
**Symbols:**

```
ffffffff813c7830-ffffffff813c78c8: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102be290)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffff8000102be290-ffff8000102be498: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04ea578)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
c04ea578-c04ea6f4: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c0000000003771a0)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
c0000000003771a0-c000000000377408: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001e0d5e)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffe0001e0d5e-ffffffe0001e0e94: __set_page_dirty_nobuffers (STB_GLOBAL)
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
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81227640)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff81227640-ffffffff812277a2: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121a7b0)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff8121a7b0-ffffffff8121a912: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812253e0)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff812253e0-ffffffff81225542: __set_page_dirty_nobuffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __set_page_dirty_nobuffers(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812346e0)
Location: mm/page-writeback.c:2465
Inline: True
Direct callers:
  - mm/page-writeback.c:redirty_page_for_writepage
  - fs/ext4/inode.c:ext4_journalled_set_page_dirty
```
**Symbols:**

```
ffffffff812346e0-ffffffff81234842: __set_page_dirty_nobuffers (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
