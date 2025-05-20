# Function: <code>__ext4_read_dirblock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a1d80)
Location: fs/ext4/namei.c:89
Inline: False
Direct callers:
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
```
**Symbols:**

```
ffffffff812a1d80-ffffffff812a2102: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d0ce0)
Location: fs/ext4/namei.c:89
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff812d0ce0-ffffffff812d1030: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e6a60)
Location: fs/ext4/namei.c:89
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff812e6a60-ffffffff812e6db0: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813165e0)
Location: fs/ext4/namei.c:89
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813165e0-ffffffff8131683c: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133ae50)
Location: fs/ext4/namei.c:90
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff8133ae50-ffffffff8133b0ac: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81369510)
Location: fs/ext4/namei.c:91
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff81369510-ffffffff813697a5: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813819b0)
Location: fs/ext4/namei.c:91
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813819b0-ffffffff81381c68: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aab50)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813aab50-ffffffff813aae52: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c3a80)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813c3a80-ffffffff813c3d82: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814102e0)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff814102e0-ffffffff8141051f: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814237b0)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff814237b0-ffffffff814239ef: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81429ed0)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff81429ed0-ffffffff8142a1e9: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147dea0)
Location: fs/ext4/namei.c:103
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff8147dea0-ffffffff8147e1b9: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81500aa0)
Location: fs/ext4/namei.c:119
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff81500aa0-ffffffff81500de7: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:124
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff8159b5d0-ffffffff8159b933: __ext4_read_dirblock (STB_LOCAL)
ffffffff8206ffb0-ffffffff8206ffd5: __ext4_read_dirblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:124
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff815d1e50-ffffffff815d21ad: __ext4_read_dirblock (STB_LOCAL)
ffffffff820efb53-ffffffff820efb6e: __ext4_read_dirblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:124
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff8160a5e0-ffffffff8160a939: __ext4_read_dirblock (STB_LOCAL)
ffffffff821ccc2b-ffffffff821ccc46: __ext4_read_dirblock.cold (STB_LOCAL)
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
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049b480)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffff80001049b480-ffff80001049b80c: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065cf94)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
c065cf94-c065d3c8: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c6040)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
c0000000005c6040-c0000000005c6478: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031e9e0)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffe00031e9e0-ffffffe00031ec36: __ext4_read_dirblock (STB_LOCAL)
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
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bc060)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813bc060-ffffffff813bc362: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813acaf0)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813acaf0-ffffffff813acdf2: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9a40)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813b9a40-ffffffff813b9d42: __ext4_read_dirblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *__ext4_read_dirblock(struct inode *inode, ext4_lblk_t block, dirblock_type_t type, const char *func, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ce5e0)
Location: fs/ext4/namei.c:102
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_empty_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_next_block
  - fs/ext4/namei.c:dx_probe
  - fs/ext4/namei.c:dx_probe
```
**Symbols:**

```
ffffffff813ce5e0-ffffffff813ce8e2: __ext4_read_dirblock (STB_LOCAL)
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
