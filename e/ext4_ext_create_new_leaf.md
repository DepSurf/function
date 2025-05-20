# Function: <code>ext4_ext_create_new_leaf</code>

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
In fs/ext4/extents.c (ffffffff812c4f0e)
Location: fs/ext4/extents.c:1347
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
In fs/ext4/extents.c (ffffffff812f4768)
Location: fs/ext4/extents.c:1353
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
In fs/ext4/extents.c (ffffffff8130a718)
Location: fs/ext4/extents.c:1353
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
In fs/ext4/extents.c (ffffffff812e8cfe)
Location: fs/ext4/extents.c:1353
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
In fs/ext4/extents.c (ffffffff8130d79e)
Location: fs/ext4/extents.c:1353
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133ca69)
Location: fs/ext4/extents.c:1347
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81354119)
Location: fs/ext4/extents.c:1347
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137c890)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8137c890-ffffffff8137cbe2: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81394f90)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81394f90-ffffffff813952e2: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e1000)
Location: fs/ext4/extents.c:1345
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813e1000-ffffffff813e1127: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f2890)
Location: fs/ext4/extents.c:1343
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813f2890-ffffffff813f29b7: ext4_ext_create_new_leaf (STB_LOCAL)
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
In fs/ext4/extents.c (ffffffff813f9435)
Location: fs/ext4/extents.c:1346
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff8144b908)
Location: fs/ext4/extents.c:1388
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff814c819e)
Location: fs/ext4/extents.c:1390
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff815607ce)
Location: fs/ext4/extents.c:1398
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff81598589)
Location: fs/ext4/extents.c:1398
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
In fs/ext4/extents.c (ffffffff815d13c9)
Location: fs/ext4/extents.c:1398
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
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
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010467cb8)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffff800010467cb8-ffff800010468028: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c06289a0)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
c06289a0-c0628d40: ext4_ext_create_new_leaf (STB_LOCAL)
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
In fs/ext4/extents.c (c000000000587980)
Location: fs/ext4/extents.c:1364
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f5a7e)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffe0002f5a7e-ffffffe0002f5d3c: ext4_ext_create_new_leaf (STB_LOCAL)
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
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138d570)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8138d570-ffffffff8138d8c2: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137e000)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8137e000-ffffffff8137e352: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138aed0)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8138aed0-ffffffff8138b222: ext4_ext_create_new_leaf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_create_new_leaf(handle_t *handle, struct inode *inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path **ppath, struct ext4_extent *newext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139ec10)
Location: fs/ext4/extents.c:1364
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8139ec10-ffffffff8139ef5d: ext4_ext_create_new_leaf (STB_LOCAL)
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
