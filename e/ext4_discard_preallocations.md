# Function: <code>ext4_discard_preallocations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d3c10)
Location: fs/ext4/mballoc.c:3940
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_clear_inode
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff812d3c10-ffffffff812d4089: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81303360)
Location: fs/ext4/mballoc.c:3954
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_clear_inode
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81303360-ffffffff813037df: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81319320)
Location: fs/ext4/mballoc.c:3961
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_clear_inode
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81319320-ffffffff8131979f: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813106c0)
Location: fs/ext4/mballoc.c:4018
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813106c0-ffffffff81310af6: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813355f0)
Location: fs/ext4/mballoc.c:4018
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813355f0-ffffffff8133599e: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81363800)
Location: fs/ext4/mballoc.c:3988
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81363800-ffffffff81363b9e: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137baa0)
Location: fs/ext4/mballoc.c:3987
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff8137baa0-ffffffff8137be3e: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a5b90)
Location: fs/ext4/mballoc.c:3989
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813a5b90-ffffffff813a5f81: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bea10)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813bea10-ffffffff813bedf9: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8140a830)
Location: fs/ext4/mballoc.c:4147
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff8140a830-ffffffff8140ac5d: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141dcb0)
Location: fs/ext4/mballoc.c:4324
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff8141dcb0-ffffffff8141e0de: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81424440)
Location: fs/ext4/mballoc.c:4857
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81424440-ffffffff814247eb: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814780e0)
Location: fs/ext4/mballoc.c:4913
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff814780e0-ffffffff8147848b: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814fa6a0)
Location: fs/ext4/mballoc.c:4968
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff814fa6a0-ffffffff814faae2: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81594ee0)
Location: fs/ext4/mballoc.c:4938
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81594ee0-ffffffff815952c5: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode, unsigned int needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815cbeb0)
Location: fs/ext4/mballoc.c:5526
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff815cbeb0-ffffffff815cc2f5: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81604960)
Location: fs/ext4/mballoc.c:5501
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_datasem_ensure_credits
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81604960-ffffffff81604d83: ext4_discard_preallocations (STB_GLOBAL)
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
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff8000104956e0)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffff8000104956e0-ffff800010495af0: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06571b4)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
c06571b4-c0657674: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005bf040)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
c0000000005bf040-c0000000005bf768: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe00031a208)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffe00031a208-ffffffe00031a6d6: ext4_discard_preallocations (STB_GLOBAL)
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
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b6ff0)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813b6ff0-ffffffff813b73d9: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a7a80)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813a7a80-ffffffff813a7e69: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b4850)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813b4850-ffffffff813b4c39: ext4_discard_preallocations (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c9470)
Location: fs/ext4/mballoc.c:4008
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_da_update_reserve_space
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/move_extent.c:ext4_move_extents
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813c9470-ffffffff813c9864: ext4_discard_preallocations (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int needed</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int needed</code>
</li>
</ul>
</details>
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
