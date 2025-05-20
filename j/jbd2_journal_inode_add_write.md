# Function: <code>jbd2_journal_inode_add_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81317290)
Location: fs/jbd2/transaction.c:2528
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81317290-ffffffff813172a5: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132d280)
Location: fs/jbd2/transaction.c:2533
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff8132d280-ffffffff8132d295: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81342450)
Location: fs/jbd2/transaction.c:2551
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81342450-ffffffff81342465: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81366a80)
Location: fs/jbd2/transaction.c:2554
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81366a80-ffffffff81366a95: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81395170)
Location: fs/jbd2/transaction.c:2557
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff81395170-ffffffff81395185: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813adee0)
Location: fs/jbd2/transaction.c:2597
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff813adee0-ffffffff813adef5: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_journal_inode_add_write(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d8250)
Location: fs/jbd2/transaction.c:2622
Inline: False
```
**Symbols:**

```
ffffffff813d8250-ffffffff813d8271: jbd2_journal_inode_add_write (STB_GLOBAL)
```
</details>
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
</ul>
