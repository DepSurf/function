# Function: <code>jbd2_journal_inode_ranged_write</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d82b0)
Location: fs/jbd2/transaction.c:2634
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813d82b0-ffffffff813d82cd: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f2330)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813f2330-ffffffff813f234d: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143f6b0)
Location: fs/jbd2/transaction.c:2699
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8143f6b0-ffffffff8143f6cd: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145b910)
Location: fs/jbd2/transaction.c:2697
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8145b910-ffffffff8145b92d: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81461250)
Location: fs/jbd2/transaction.c:2702
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff81461250-ffffffff8146126d: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b6740)
Location: fs/jbd2/transaction.c:2702
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff814b6740-ffffffff814b675d: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81540140)
Location: fs/jbd2/transaction.c:2720
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff81540140-ffffffff8154016c: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dec60)
Location: fs/jbd2/transaction.c:2728
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff815dec60-ffffffff815dec8c: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff816166c0)
Location: fs/jbd2/transaction.c:2707
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journal_folio_buffers
```
**Symbols:**

```
ffffffff816166c0-ffffffff816166ec: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164f4e0)
Location: fs/jbd2/transaction.c:2717
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_journal_folio_buffers
```
**Symbols:**

```
ffffffff8164f4e0-ffffffff8164f50c: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104ccb10)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffff8000104ccb10-ffff8000104ccb64: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c06903d4)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c06903d4-c069041c: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000606230)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
c000000000606230-c000000000606258: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000345430)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffe000345430-ffffffe000345478: jbd2_journal_inode_ranged_write (STB_GLOBAL)
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
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ea910)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813ea910-ffffffff813ea92d: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813db390)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813db390-ffffffff813db3ad: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e7c90)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813e7c90-ffffffff813e7cad: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_write(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fd4b0)
Location: fs/jbd2/transaction.c:2631
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813fd4b0-ffffffff813fd4cd: jbd2_journal_inode_ranged_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
