# Function: <code>ext4_ext_split</code>

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
In fs/ext4/extents.c (ffffffff812c514a)
Location: fs/ext4/extents.c:1024
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff812f4999)
Location: fs/ext4/extents.c:1030
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff8130a949)
Location: fs/ext4/extents.c:1030
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e8fd1)
Location: fs/ext4/extents.c:1030
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130da71)
Location: fs/ext4/extents.c:1030
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133a200)
Location: fs/ext4/extents.c:1024
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8133a200-ffffffff8133ab28: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81351590)
Location: fs/ext4/extents.c:1024
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81351590-ffffffff81351eb8: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ae30)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff8137ae30-ffffffff8137b7d9: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81393300)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff81393300-ffffffff81393ca9: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813df690)
Location: fs/ext4/extents.c:1005
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff813df690-ffffffff813dfea4: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f0f50)
Location: fs/ext4/extents.c:1003
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff813f0f50-ffffffff813f1764: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f73d0)
Location: fs/ext4/extents.c:1004
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813f73d0-ffffffff813f7bec: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81448ea0)
Location: fs/ext4/extents.c:1042
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81448ea0-ffffffff8144968b: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c4e50)
Location: fs/ext4/extents.c:1044
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff814c4e50-ffffffff814c5657: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155d3a0)
Location: fs/ext4/extents.c:1052
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8155d3a0-ffffffff8155dbbd: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815951b0)
Location: fs/ext4/extents.c:1052
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff815951b0-ffffffff815959de: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cde50)
Location: fs/ext4/extents.c:1052
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff815cde50-ffffffff815ce68d: ext4_ext_split (STB_LOCAL)
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
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010466030)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffff800010466030-ffff8000104669a8: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0626a54)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
c0626a54-c06274c8: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000583d60)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
c000000000583d60-c0000000005848c8: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f4190)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffe0002f4190-ffffffe0002f4a20: ext4_ext_split (STB_LOCAL)
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
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138b8e0)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff8138b8e0-ffffffff8138c289: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137c370)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff8137c370-ffffffff8137cd19: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389240)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff81389240-ffffffff81389be9: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_split(handle_t *handle, struct inode *inode, unsigned int flags, struct ext4_ext_path *path, struct ext4_extent *newext, int at);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139cf60)
Location: fs/ext4/extents.c:1028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
```
**Symbols:**

```
ffffffff8139cf60-ffffffff8139d8fb: ext4_ext_split (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
