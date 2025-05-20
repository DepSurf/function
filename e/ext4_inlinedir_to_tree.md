# Function: <code>ext4_inlinedir_to_tree</code>

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
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138f270)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8138f270-ffffffff8138f66e: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a7cd0)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813a7cd0-ffffffff813a80c8: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f3d30)
Location: fs/ext4/inline.c:1329
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813f3d30-ffffffff813f4151: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814064c0)
Location: fs/ext4/inline.c:1329
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff814064c0-ffffffff814068e1: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140c9a0)
Location: fs/ext4/inline.c:1335
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8140c9a0-ffffffff8140cda3: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145f7f0)
Location: fs/ext4/inline.c:1352
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8145f7f0-ffffffff8145fbea: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814ddf00)
Location: fs/ext4/inline.c:1348
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff814ddf00-ffffffff814de321: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81576f60)
Location: fs/ext4/inline.c:1347
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81576f60-ffffffff81577381: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ae470)
Location: fs/ext4/inline.c:1330
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff815ae470-ffffffff815ae8b3: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e7230)
Location: fs/ext4/inline.c:1329
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff815e7230-ffffffff815e7673: ext4_inlinedir_to_tree (STB_GLOBAL)
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
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047b610)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffff80001047b610-ffff80001047b934: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063ceac)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
c063ceac-c063d1d8: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059ea20)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
c00000000059ea20-c00000000059ee9c: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000305a7e)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffe000305a7e-ffffffe000305cee: ext4_inlinedir_to_tree (STB_GLOBAL)
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
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a02b0)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813a02b0-ffffffff813a06a8: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81390d40)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81390d40-ffffffff81391138: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139db10)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8139db10-ffffffff8139df08: ext4_inlinedir_to_tree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_inlinedir_to_tree(struct file *dir_file, struct inode *dir, ext4_lblk_t block, struct dx_hash_info *hinfo, __u32 start_hash, __u32 start_minor_hash, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b2080)
Location: fs/ext4/inline.c:1327
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813b2080-ffffffff813b2478: ext4_inlinedir_to_tree (STB_GLOBAL)
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
