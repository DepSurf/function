# Function: <code>ext4_add_new_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812bff84)
Location: fs/ext4/resize.c:1150
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812ef4c1)
Location: fs/ext4/resize.c:1150
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81305491)
Location: fs/ext4/resize.c:1150
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8131f8f0)
Location: fs/ext4/resize.c:1151
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8131f8f0-ffffffff81320410: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81343f90)
Location: fs/ext4/resize.c:1177
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81343f90-ffffffff81344ad4: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1180
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81371f80-ffffffff81372b46: ext4_add_new_descs (STB_LOCAL)
ffffffff813751f0-ffffffff81375205: ext4_add_new_descs.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1180
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8138a490-ffffffff8138af96: ext4_add_new_descs (STB_LOCAL)
ffffffff8138d608-ffffffff8138d61d: ext4_add_new_descs.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b5a20)
Location: fs/ext4/resize.c:1188
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813b5a20-ffffffff813b60f5: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813cec20)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813cec20-ffffffff813cf2dd: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141bfb0)
Location: fs/ext4/resize.c:1197
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8141bfb0-ffffffff8141c0de: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142fd20)
Location: fs/ext4/resize.c:1202
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8142fd20-ffffffff8142fe5b: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81436b26)
Location: fs/ext4/resize.c:1202
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8148a761)
Location: fs/ext4/resize.c:1211
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8150e5a6)
Location: fs/ext4/resize.c:1233
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815a9412)
Location: fs/ext4/resize.c:1249
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff815dfc72)
Location: fs/ext4/resize.c:1249
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81618749)
Location: fs/ext4/resize.c:1251
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a7568)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffff8000104a7568-ffff8000104a7bec: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c06696e0)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
c06696e0-c0669dc4: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d5258)
Location: fs/ext4/resize.c:1219
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000328018)
Location: fs/ext4/resize.c:1219
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
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
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c7200)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813c7200-ffffffff813c78bd: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b7c80)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813b7c80-ffffffff813b833d: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c4690)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813c4690-ffffffff813c4d4d: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t *handle, struct super_block *sb, ext4_group_t group, struct inode *resize_inode, ext4_group_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813d9870)
Location: fs/ext4/resize.c:1219
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813d9870-ffffffff813d9f40: ext4_add_new_descs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
