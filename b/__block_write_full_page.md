# Function: <code>__block_write_full_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff812469d0)
Location: fs/buffer.c:1701
Inline: True
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff812469d0-ffffffff81246d70: __block_write_full_page.constprop.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126d0d0)
Location: fs/buffer.c:1691
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8126d0d0-ffffffff8126d43c: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81280330)
Location: fs/buffer.c:1734
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff81280330-ffffffff8128068b: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128dc10)
Location: fs/buffer.c:1729
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8128dc10-ffffffff8128dfde: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b0800)
Location: fs/buffer.c:1689
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff812b0800-ffffffff812b0bed: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d85f0)
Location: fs/buffer.c:1660
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff812d85f0-ffffffff812d8a25: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812edac0)
Location: fs/buffer.c:1668
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff812edac0-ffffffff812edefb: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff81311d20-ffffffff81311d33: __block_write_full_page.cold (STB_LOCAL)
ffffffff8130f290-ffffffff8130f6be: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813221f0)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff813221f0-ffffffff81322633: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135c450)
Location: fs/buffer.c:1713
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8135c450-ffffffff8135c8c3: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136a8d0)
Location: fs/buffer.c:1712
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8136a8d0-ffffffff8136ad62: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136ffe0)
Location: fs/buffer.c:1732
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8136ffe0-ffffffff81370476: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1711
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff81cc454f-ffffffff81cc45a9: __block_write_full_page.cold (STB_LOCAL)
ffffffff813beb60-ffffffff813beff2: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1709
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff81e771e5-ffffffff81e7723f: __block_write_full_page.cold (STB_LOCAL)
ffffffff814472b0-ffffffff814477dd: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1694
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
```
**Symbols:**

```
ffffffff82069242-ffffffff820692a4: __block_write_full_page.cold (STB_LOCAL)
ffffffff814d5ef0-ffffffff814d63fa: __block_write_full_page (STB_GLOBAL)
```
</details>
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
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103daf78)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffff8000103daf78-ffff8000103db5a0: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b4300)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:block_write_full_page
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
c05b4300-c05b492c: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e0200)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
c0000000004e0200-c0000000004e0870: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000293930)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffe000293930-ffffffe000293d20: __block_write_full_page (STB_GLOBAL)
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
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a7d0)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8131a7d0-ffffffff8131ac13: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130b370)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff8130b370-ffffffff8130b7b3: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813182a0)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff813182a0-ffffffff813186e3: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __block_write_full_page(struct inode *inode, struct page *page, get_block_t *get_block, struct writeback_control *wbc, bh_end_io_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81329ec0)
Location: fs/buffer.c:1669
Inline: False
Direct callers:
  - fs/buffer.c:nobh_writepage
```
**Symbols:**

```
ffffffff81329ec0-ffffffff8132a2eb: __block_write_full_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
