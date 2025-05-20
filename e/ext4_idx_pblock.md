# Function: <code>ext4_idx_pblock</code>

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
In fs/ext4/extents.c (ffffffff812c301e)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
```
In fs/ext4/migrate.c (ffffffff812cc4c1)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff812f6149)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff812fbe01)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff8130c0f9)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff81311db1)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff812ea81e)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff81313841)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff8130f2be)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff81338001)
Location: fs/ext4/ext4_extents.h:233
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff8133d9f8)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff81366545)
Location: fs/ext4/ext4_extents.h:222
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff81355c9c)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff8137e9a5)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff8137f66d)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff813a7e25)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff81397d7d)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff813c0c55)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff813e3a40)
Location: fs/ext4/ext4_extents.h:238
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff8140cc55)
Location: fs/ext4/ext4_extents.h:238
Inline: True
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
In fs/ext4/extents.c (ffffffff813f528e)
Location: fs/ext4/ext4_extents.h:238
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff814200b5)
Location: fs/ext4/ext4_extents.h:238
Inline: True
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
In fs/ext4/extents.c (ffffffff813fb5ce)
Location: fs/ext4/ext4_extents.h:238
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:ext4_ext_precache
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff814268f5)
Location: fs/ext4/ext4_extents.h:238
Inline: True
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
In fs/ext4/extents.c (ffffffff81448cff)
Location: fs/ext4/ext4_extents.h:239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:ext4_valid_extent_entries
  - fs/ext4/extents.c:ext4_valid_extent_entries
```
```
In fs/ext4/migrate.c (ffffffff8147a585)
Location: fs/ext4/ext4_extents.h:239
Inline: True
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
In fs/ext4/extents.c (ffffffff814c5b6f)
Location: fs/ext4/ext4_extents.h:239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff814fc8c5)
Location: fs/ext4/ext4_extents.h:239
Inline: True
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
In fs/ext4/extents.c (ffffffff8155e0ff)
Location: fs/ext4/ext4_extents.h:239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff81597035)
Location: fs/ext4/ext4_extents.h:239
Inline: True
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
In fs/ext4/extents.c (ffffffff81595f0f)
Location: fs/ext4/ext4_extents.h:239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff815cda75)
Location: fs/ext4/ext4_extents.h:239
Inline: True
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
In fs/ext4/extents.c (ffffffff815cebbf)
Location: fs/ext4/ext4_extents.h:239
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_try_to_merge_up
  - fs/ext4/extents.c:ext4_ext_grow_indepth
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__read_extent_tree_block
  - fs/ext4/extents.c:__ext4_ext_check
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff816062f5)
Location: fs/ext4/ext4_extents.h:239
Inline: True
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
In fs/ext4/extents.c (ffff80001046a9dc)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffff800010497fd8)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (c062b7f4)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (c0659a48)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (c000000000589b68)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_insert_extent
  - fs/ext4/extents.c:ext4_ext_try_to_merge
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (c0000000005c22b0)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffe0002f820e)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffe00031c282)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff8139035d)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff813b9235)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff81380ded)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff813a9cc5)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff8138dcbd)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff813b6a95)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
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
In fs/ext4/extents.c (ffffffff813a1a61)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_rm_idx
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_search_right
  - fs/ext4/extents.c:ext4_ext_create_new_leaf
  - fs/ext4/extents.c:ext4_find_extent
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/migrate.c (ffffffff813cb7a5)
Location: fs/ext4/ext4_extents.h:235
Inline: True
Inline callers:
  - fs/ext4/migrate.c:free_ext_idx
```
</details>
</li>
</ul>

## Differences
