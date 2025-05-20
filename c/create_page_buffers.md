# Function: <code>create_page_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243a20)
Location: fs/buffer.c:1663
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin
```
**Symbols:**

```
ffffffff81243a20-ffffffff81243a68: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126ba90)
Location: fs/buffer.c:1653
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8126ba90-ffffffff8126bae7: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127ebd0)
Location: fs/buffer.c:1696
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8127ebd0-ffffffff8127ec27: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128caa0)
Location: fs/buffer.c:1691
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8128caa0-ffffffff8128caf7: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812aeff0)
Location: fs/buffer.c:1650
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff812aeff0-ffffffff812af047: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d74d0)
Location: fs/buffer.c:1621
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff812d74d0-ffffffff812d7527: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec9e0)
Location: fs/buffer.c:1629
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff812ec9e0-ffffffff812eca38: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130e180)
Location: fs/buffer.c:1630
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8130e180-ffffffff8130e1d8: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813211a0)
Location: fs/buffer.c:1630
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff813211a0-ffffffff813211f8: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135ac80)
Location: fs/buffer.c:1674
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8135ac80-ffffffff8135acdb: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81368ac0)
Location: fs/buffer.c:1673
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff81368ac0-ffffffff81368b1b: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136ff80)
Location: fs/buffer.c:1693
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8136ff80-ffffffff8136ffdb: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1672
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff813beae0-ffffffff813beb52: create_page_buffers (STB_LOCAL)
ffffffff81cc452f-ffffffff81cc454f: create_page_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1670
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff814455d0-ffffffff81445680: create_page_buffers (STB_LOCAL)
ffffffff81e76f61-ffffffff81e76f81: create_page_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1655
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff814d4e60-ffffffff814d4f10: create_page_buffers (STB_LOCAL)
ffffffff82069114-ffffffff82069134: create_page_buffers.cold (STB_LOCAL)
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
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9500)
Location: fs/buffer.c:1630
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffff8000103d9500-ffff8000103d958c: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2230)
Location: fs/buffer.c:1630
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
c05b2230-c05b22a0: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dd5f0)
Location: fs/buffer.c:1630
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
c0000000004dd5f0-c0000000004dd69c: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000292972)
Location: fs/buffer.c:1630
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffe000292972-ffffffe0002929e8: create_page_buffers (STB_LOCAL)
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
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81319780)
Location: fs/buffer.c:1630
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff81319780-ffffffff813197d8: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130a340)
Location: fs/buffer.c:1630
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff8130a340-ffffffff8130a398: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81317250)
Location: fs/buffer.c:1630
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff81317250-ffffffff813172a8: create_page_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *create_page_buffers(struct page *page, struct inode *inode, unsigned int b_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328600)
Location: fs/buffer.c:1630
Inline: True
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff81328600-ffffffff81328658: create_page_buffers (STB_LOCAL)
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
