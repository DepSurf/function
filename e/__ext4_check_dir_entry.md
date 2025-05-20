# Function: <code>__ext4_check_dir_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81290be0)
Location: fs/ext4/dir.c:60
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff81290be0-ffffffff81290d02: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812be0f0)
Location: fs/ext4/dir.c:60
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812be0f0-ffffffff812be212: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812d3730)
Location: fs/ext4/dir.c:60
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812d3730-ffffffff812d3852: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812e5110)
Location: fs/ext4/dir.c:60
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff812e5110-ffffffff812e5247: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81309b40)
Location: fs/ext4/dir.c:61
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81309b40-ffffffff81309c77: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81337ac0)
Location: fs/ext4/dir.c:62
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81337ac0-ffffffff81337bed: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8134ed40)
Location: fs/ext4/dir.c:62
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134ed40-ffffffff8134ee6d: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81377db0)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81377db0-ffffffff81377ed9: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81390130)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81390130-ffffffff81390278: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813dc0e5)
Location: fs/ext4/dir.c:66
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813db6e0-ffffffff813db823: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813edb75)
Location: fs/ext4/dir.c:66
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_check_all_de
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813ed110-ffffffff813ed253: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813f3640)
Location: fs/ext4/dir.c:78
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813f3640-ffffffff813f38b8: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81445700)
Location: fs/ext4/dir.c:78
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81445700-ffffffff81445978: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff814c1770)
Location: fs/ext4/dir.c:78
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff814c1770-ffffffff814c1a1c: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81559a20)
Location: fs/ext4/dir.c:78
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81559a20-ffffffff81559ccc: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81591850)
Location: fs/ext4/dir.c:78
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81591850-ffffffff81591aec: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff815ca5c0)
Location: fs/ext4/dir.c:78
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff815ca5c0-ffffffff815ca85c: __ext4_check_dir_entry (STB_GLOBAL)
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
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff8000104629e8)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffff8000104629e8-ffff800010462b7c: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c0622c38)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c0622c38-c0622da4: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c00000000057f2b0)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c00000000057f2b0-c00000000057f4cc: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f1448)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffe0002f1448-ffffffe0002f155e: __ext4_check_dir_entry (STB_GLOBAL)
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
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81388710)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81388710-ffffffff81388858: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813791a0)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813791a0-ffffffff813792e8: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81386070)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81386070-ffffffff813861b8: __ext4_check_dir_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_check_dir_entry(const char *function, unsigned int line, struct inode *dir, struct file *filp, struct ext4_dir_entry_2 *de, struct buffer_head *bh, char *buf, int size, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81399d60)
Location: fs/ext4/dir.c:66
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_check_all_de
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_generic_delete_entry
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81399d60-ffffffff81399ea8: __ext4_check_dir_entry (STB_GLOBAL)
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
