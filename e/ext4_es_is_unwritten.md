# Function: <code>ext4_es_is_unwritten</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/file.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:114
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:114
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81341fba)
Location: fs/ext4/extents_status.h:114
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81351380)
Location: fs/ext4/extents_status.h:114
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135b639)
Location: fs/ext4/extents_status.h:166
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8136a222)
Location: fs/ext4/extents_status.h:166
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81384652)
Location: fs/ext4/extents_status.h:166
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81393e28)
Location: fs/ext4/extents_status.h:166
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139178d)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8139d2d2)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813ac7ba)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd26d)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813e6e8f)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff813f8a9a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813eeb5d)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813f914f)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff8140b179)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fd469)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
```
In fs/ext4/extents_status.c (ffffffff8140109b)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff8141132a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814473d0)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814513e1)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff81464180)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c3a5a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814ceb4a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff814e3a30)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155bd9a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815673ba)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff8157cf30)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81593bb0)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8159f58a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff815b42dd)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cc8a0)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815d80da)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/inode.c (ffffffff815ed0dd)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010464330)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffff8000104704f4)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffff800010480f7c)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062538c)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c0631914)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (c064207c)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582584)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c000000000590b8c)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (c0000000005a53f0)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f321a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffe0002fcc0e)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffe000309cbe)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389d6d)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813958b2)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a4d9a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a7fd)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81386342)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8139582a)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813876cd)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81393212)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a25fa)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b3ad)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813a72a5)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813b6cda)
Location: fs/ext4/extents_status.h:167
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
</details>
</li>
</ul>

## Differences
