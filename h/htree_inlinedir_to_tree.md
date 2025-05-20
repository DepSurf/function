# Function: <code>htree_inlinedir_to_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e17b0)
Location: fs/ext4/inline.c:1315
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff812e17b0-ffffffff812e1b6b: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81311700)
Location: fs/ext4/inline.c:1314
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81311700-ffffffff81311ac1: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81327640)
Location: fs/ext4/inline.c:1331
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81327640-ffffffff81327a01: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fb4a0)
Location: fs/ext4/inline.c:1333
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff812fb4a0-ffffffff812fb904: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131fc80)
Location: fs/ext4/inline.c:1324
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8131fc80-ffffffff81320051: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134dd90)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8134dd90-ffffffff8134e154: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int htree_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81365f30)
Location: fs/ext4/inline.c:1330
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81365f30-ffffffff813662f4: htree_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
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
</ul>
