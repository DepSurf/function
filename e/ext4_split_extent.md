# Function: <code>ext4_split_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c6400)
Location: fs/ext4/extents.c:3300
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff812c6400-ffffffff812c6580: ext4_split_extent.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f5c50)
Location: fs/ext4/extents.c:3314
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_convert_extents
```
**Symbols:**

```
ffffffff812f5c50-ffffffff812f5dd4: ext4_split_extent.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130bc00)
Location: fs/ext4/extents.c:3314
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_convert_extents
```
**Symbols:**

```
ffffffff8130bc00-ffffffff8130bd84: ext4_split_extent.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812ea330)
Location: fs/ext4/extents.c:3315
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
```
**Symbols:**

```
ffffffff812ea330-ffffffff812ea4c3: ext4_split_extent.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130edd0)
Location: fs/ext4/extents.c:3315
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
```
**Symbols:**

```
ffffffff8130edd0-ffffffff8130ef63: ext4_split_extent.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133d590)
Location: fs/ext4/extents.c:3309
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
```
**Symbols:**

```
ffffffff8133d590-ffffffff8133d71f: ext4_split_extent.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff81354c40)
Location: fs/ext4/extents.c:3371
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_convert_extents
```
**Symbols:**

```
ffffffff81354c40-ffffffff81354dcf: ext4_split_extent.isra.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137e520)
Location: fs/ext4/extents.c:3391
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff8137e520-ffffffff8137e6b8: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff81396c40)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff81396c40-ffffffff81396dd8: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e22c0)
Location: fs/ext4/extents.c:3277
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813e22c0-ffffffff813e2454: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f3b20)
Location: fs/ext4/extents.c:3276
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813f3b20-ffffffff813f3cb4: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f9ea0)
Location: fs/ext4/extents.c:3282
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813f9ea0-ffffffff813fa035: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144c2e0)
Location: fs/ext4/extents.c:3320
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff8144c2e0-ffffffff8144c475: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c8c50)
Location: fs/ext4/extents.c:3319
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff814c8c50-ffffffff814c8df9: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81561290)
Location: fs/ext4/extents.c:3324
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff81561290-ffffffff81561439: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81599020)
Location: fs/ext4/extents.c:3324
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff81599020-ffffffff815991c9: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d1e60)
Location: fs/ext4/extents.c:3300
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff815d1e60-ffffffff815d2009: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffff800010469938)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffff800010469938-ffff800010469ad4: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_split_extent(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, struct ext4_map_blocks *map, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062a6d0)
Location: fs/ext4/extents.c:3437
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
c062a6d0-c062a860: ext4_split_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (c000000000588730)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
c000000000588730-c000000000588948: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f7294)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffe0002f7294-ffffffe0002f73f4: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138f220)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff8138f220-ffffffff8138f3b8: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137fcb0)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff8137fcb0-ffffffff8137fe48: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138cb80)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff8138cb80-ffffffff8138cd18: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a08d0)
Location: fs/ext4/extents.c:3437
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_split_convert_extents
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
```
**Symbols:**

```
ffffffff813a08d0-ffffffff813a0a68: ext4_split_extent.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
