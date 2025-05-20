# Function: <code>ext4_ext_mark_initialized</code>

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
In fs/ext4/extents.c (ffffffff812c612f)
Location: fs/ext4/ext4_extents.h:211
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff812f8474)
Location: fs/ext4/ext4_extents.h:211
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff8130e440)
Location: fs/ext4/ext4_extents.h:211
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff812ebafc)
Location: fs/ext4/ext4_extents.h:211
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff813105a8)
Location: fs/ext4/ext4_extents.h:211
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff8133e41f)
Location: fs/ext4/ext4_extents.h:200
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff81354f7f)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137f0d2)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813977f2)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e27f9)
Location: fs/ext4/ext4_extents.h:216
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff813f7ab3)
Location: fs/ext4/ext4_extents.h:216
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_convert_unwritten_extents_endio
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff81454c72)
Location: fs/ext4/ext4_extents.h:216
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff813fdf43)
Location: fs/ext4/ext4_extents.h:216
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff8145a3a2)
Location: fs/ext4/ext4_extents.h:216
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff81450243)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff814ae27c)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff814cd2fb)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff815369af)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff81565a3b)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff815d4d5f)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff8159d6cf)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff8160c94f)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
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
In fs/ext4/extents.c (ffffffff815d631f)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
```
In fs/ext4/fast_commit.c (ffffffff8164570f)
Location: fs/ext4/ext4_extents.h:217
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_inode_data
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff80001046a3e8)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062b238)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (c0000000005893a4)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffe0002f7cc0)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138fdd2)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81380862)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138d732)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a14c2)
Location: fs/ext4/ext4_extents.h:213
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
</ul>

## Differences
