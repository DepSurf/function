# Function: <code>ext4_ext_try_to_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c4710)
Location: fs/ext4/extents.c:1847
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
```
**Symbols:**

```
ffffffff812c4710-ffffffff812c484e: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f3f60)
Location: fs/ext4/extents.c:1859
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff812f3f60-ffffffff812f409e: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81309f10)
Location: fs/ext4/extents.c:1859
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81309f10-ffffffff8130a04e: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e85e0)
Location: fs/ext4/extents.c:1859
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff812e85e0-ffffffff812e8721: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d080)
Location: fs/ext4/extents.c:1859
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8130d080-ffffffff8130d1c1: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133c270)
Location: fs/ext4/extents.c:1853
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8133c270-ffffffff8133c3b6: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81353920)
Location: fs/ext4/extents.c:1853
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81353920-ffffffff81353a66: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137d460)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8137d460-ffffffff8137d5a6: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81395b80)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81395b80-ffffffff81395cc6: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ddb20)
Location: fs/ext4/extents.c:1839
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813ddb20-ffffffff813ddc75: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ef410)
Location: fs/ext4/extents.c:1838
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813ef410-ffffffff813ef565: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f58d0)
Location: fs/ext4/extents.c:1841
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff813f58d0-ffffffff813f5a25: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81447620)
Location: fs/ext4/extents.c:1879
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81447620-ffffffff81447775: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c3d10)
Location: fs/ext4/extents.c:1880
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff814c3d10-ffffffff814c3d98: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155c1d0)
Location: fs/ext4/extents.c:1888
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8155c1d0-ffffffff8155c258: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81593fd0)
Location: fs/ext4/extents.c:1888
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff81593fd0-ffffffff81594058: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cccc0)
Location: fs/ext4/extents.c:1888
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_shrink_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:convert_initialized_extent
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff815cccc0-ffffffff815ccd48: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104689b0)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffff8000104689b0-ffff800010468b14: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062973c)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
c062973c-c0629890: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000586f40)
Location: fs/ext4/extents.c:1870
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
c000000000586f40-c0000000005870c8: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f651e)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffe0002f651e-ffffffe0002f6628: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138e160)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8138e160-ffffffff8138e2a6: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ebf0)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8137ebf0-ffffffff8137ed36: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138bac0)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8138bac0-ffffffff8138bc06: ext4_ext_try_to_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ext4_ext_try_to_merge(handle_t *handle, struct inode *inode, struct ext4_ext_path *path, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139f810)
Location: fs/ext4/extents.c:1870
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_insert_extent
```
**Symbols:**

```
ffffffff8139f810-ffffffff8139f956: ext4_ext_try_to_merge (STB_LOCAL)
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
