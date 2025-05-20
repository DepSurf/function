# Function: <code>ext4_es_is_delayed</code>

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
Location: fs/ext4/extents_status.h:118
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:118
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
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:118
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff8130abfa)
Location: fs/ext4/extents_status.h:118
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
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
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:118
Inline: True
```
```
In fs/ext4/extents_status.c (ffffffff81320bfa)
Location: fs/ext4/extents_status.h:118
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
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
In fs/ext4/extents_status.c (ffffffff812efba2)
Location: fs/ext4/extents_status.h:118
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:118
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
In fs/ext4/extents_status.c (ffffffff8131469e)
Location: fs/ext4/extents_status.h:119
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:119
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
In fs/ext4/extents_status.c (ffffffff81342516)
Location: fs/ext4/extents_status.h:119
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
```
In fs/ext4/inode.c (ffffffff8135137c)
Location: fs/ext4/extents_status.h:119
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81350420)
Location: fs/ext4/extents_status.h:171
Inline: False
```
```
In fs/ext4/extents_status.c (ffffffff8135b62c)
Location: fs/ext4/extents_status.h:171
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8136a21d)
Location: fs/ext4/extents_status.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff81350420-ffffffff8135042c: ext4_es_is_delayed (STB_LOCAL)
ffffffff813675f0-ffffffff813675fc: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813790e0)
Location: fs/ext4/extents_status.h:171
Inline: False
```
```
In fs/ext4/extents_status.c (ffffffff81384646)
Location: fs/ext4/extents_status.h:171
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81390a00)
Location: fs/ext4/extents_status.h:171
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff813790e0-ffffffff813790ec: ext4_es_is_delayed (STB_LOCAL)
ffffffff813909e0-ffffffff813909ec: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813917a8)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8139d2c6)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a9460)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff81391490-ffffffff8139149c: ext4_es_is_delayed (STB_LOCAL)
ffffffff813a9440-ffffffff813a944c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd288)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813e6e82)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff813f53b0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff813dcd40-ffffffff813dcd4c: ext4_es_is_delayed (STB_LOCAL)
ffffffff813f5390-ffffffff813f539c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813eeb78)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813f9142)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff81407b50)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff813ee680-ffffffff813ee68c: ext4_es_is_delayed (STB_LOCAL)
ffffffff81407b30-ffffffff81407b3c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fd482)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
```
In fs/ext4/extents_status.c (ffffffff8140108e)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff8140dfd0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff813f4c50-ffffffff813f4c5c: ext4_es_is_delayed (STB_LOCAL)
ffffffff8140dfa0-ffffffff8140dfac: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814473ec)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814513ce)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff81460e90)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff81446ea0-ffffffff81446eac: ext4_es_is_delayed (STB_LOCAL)
ffffffff81460e60-ffffffff81460e6c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c3a76)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814ceb37)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff814df8d0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff814c31a0-ffffffff814c31b2: ext4_es_is_delayed (STB_LOCAL)
ffffffff814df880-ffffffff814df892: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155bdb6)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815673a7)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff81578a50)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff8155b5a0-ffffffff8155b5b2: ext4_es_is_delayed (STB_LOCAL)
ffffffff815789e0-ffffffff815789f2: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81593bcc)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8159f577)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff815afff0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff815933c0-ffffffff815933d2: ext4_es_is_delayed (STB_LOCAL)
ffffffff815aff80-ffffffff815aff92: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cc8bc)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815d80c7)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (ffffffff815ed0e2)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff815cc0b0-ffffffff815cc0c2: ext4_es_is_delayed (STB_LOCAL)
ffffffff815e8d30-ffffffff815e8d42: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010464344)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffff8000104704e8)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffff80001047d328)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffff800010464068-ffff800010464074: ext4_es_is_delayed (STB_LOCAL)
ffff80001047d308-ffff80001047d314: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c06253a0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c0631904)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (c063e81c)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
c0624618-c0624630: ext4_es_is_delayed (STB_LOCAL)
c063e7dc-c063e7f4: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c00000000058259c)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c000000000590b7c)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_free_extent
```
```
In fs/ext4/inode.c (c0000000005a0960)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
c0000000005813d0-c0000000005813dc: ext4_es_is_delayed (STB_LOCAL)
c0000000005a0930-c0000000005a093c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f322e)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffe0002fcc04)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffe000306bc2)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffe0002f26d2-ffffffe0002f26e4: ext4_es_is_delayed (STB_LOCAL)
ffffffe000306b9a-ffffffe000306bac: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389d88)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813958a6)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a1a40)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff81389a70-ffffffff81389a7c: ext4_es_is_delayed (STB_LOCAL)
ffffffff813a1a20-ffffffff813a1a2c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a818)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81386336)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813924d0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff8137a500-ffffffff8137a50c: ext4_es_is_delayed (STB_LOCAL)
ffffffff813924b0-ffffffff813924bc: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813876e8)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81393206)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8139f2a0)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff813873d0-ffffffff813873dc: ext4_es_is_delayed (STB_LOCAL)
ffffffff8139f280-ffffffff8139f28c: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delayed(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b3c8)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813a7299)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:ext4_clear_inode_es
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813b3800)
Location: fs/ext4/extents_status.h:172
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_es_is_delonly
```
**Symbols:**

```
ffffffff8139b0b0-ffffffff8139b0bc: ext4_es_is_delayed (STB_LOCAL)
ffffffff813b37e0-ffffffff813b37ec: ext4_es_is_delayed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
