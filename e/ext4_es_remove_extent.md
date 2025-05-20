# Function: <code>ext4_es_remove_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812dc170)
Location: fs/ext4/extents_status.c:944
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff812dc170-ffffffff812dc21d: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8130baa0)
Location: fs/ext4/extents_status.c:944
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8130baa0-ffffffff8130bb4a: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81321aa0)
Location: fs/ext4/extents_status.c:944
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81321aa0-ffffffff81321b4a: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812f09f0)
Location: fs/ext4/extents_status.c:944
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff812f09f0-ffffffff812f0a94: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81315520)
Location: fs/ext4/extents_status.c:945
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81315520-ffffffff813155c7: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81343330)
Location: fs/ext4/extents_status.c:944
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81343330-ffffffff813433d5: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135af50)
Location: fs/ext4/extents_status.c:1066
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff8135af50-ffffffff8135aff5: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383f70)
Location: fs/ext4/extents_status.c:1066
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81383f70-ffffffff81384017: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139ca70)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff8139ca70-ffffffff8139cb64: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e81b0)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813e81b0-ffffffff813e82a7: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fa470)
Location: fs/ext4/extents_status.c:1433
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813fa470-ffffffff813fa560: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400830)
Location: fs/ext4/extents_status.c:1433
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81400830-ffffffff81400920: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81452e40)
Location: fs/ext4/extents_status.c:1433
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81452e40-ffffffff81452f2d: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814d0300)
Location: fs/ext4/extents_status.c:1433
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff814d0300-ffffffff814d0419: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81568c60)
Location: fs/ext4/extents_status.c:1431
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81568c60-ffffffff81568d79: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815a08c0)
Location: fs/ext4/extents_status.c:1463
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff815a08c0-ffffffff815a0a3c: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d95c0)
Location: fs/ext4/extents_status.c:1495
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff815d95c0-ffffffff815d974c: ext4_es_remove_extent (STB_GLOBAL)
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
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046fa28)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffff80001046fa28-ffff80001046fba8: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0630fa8)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
c0630fa8-c06310f0: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058ff30)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
c00000000058ff30-c0000000005900b8: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fc44c)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffe0002fc44c-ffffffe0002fc524: ext4_es_remove_extent (STB_GLOBAL)
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
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81395050)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81395050-ffffffff81395144: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81385ae0)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff81385ae0-ffffffff81385bd4: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813929b0)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813929b0-ffffffff81392aa4: ext4_es_remove_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_es_remove_extent(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6940)
Location: fs/ext4/extents_status.c:1415
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/super.c:ext4_clear_inode
```
**Symbols:**

```
ffffffff813a6940-ffffffff813a6a58: ext4_es_remove_extent (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
