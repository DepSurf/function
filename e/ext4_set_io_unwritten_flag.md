# Function: <code>ext4_set_io_unwritten_flag</code>

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
In fs/ext4/inode.c (ffffffff8129c059)
Location: fs/ext4/ext4.h:1447
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
```
In fs/ext4/extents.c (ffffffff812c7bae)
Location: fs/ext4/ext4.h:1447
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/inode.c (ffffffff812c9bc6)
Location: fs/ext4/ext4.h:3257
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff812df7ce)
Location: fs/ext4/ext4.h:3235
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff81303b1e)
Location: fs/ext4/ext4.h:3251
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff81328516)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff81356235)
Location: fs/ext4/ext4.h:3203
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff8136e501)
Location: fs/ext4/ext4.h:3227
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff81397386)
Location: fs/ext4/ext4.h:3314
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff813afdb6)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff813f9791)
Location: fs/ext4/ext4.h:3494
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140bd8c)
Location: fs/ext4/ext4.h:3693
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
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
In fs/ext4/inode.c (ffffffff81411f4c)
Location: fs/ext4/ext4.h:3758
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
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
In fs/ext4/inode.c (ffffffff81467a58)
Location: fs/ext4/ext4.h:3840
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (ffffffff814e4577)
Location: fs/ext4/ext4.h:3805
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
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
In fs/ext4/inode.c (ffffffff8157d857)
Location: fs/ext4/ext4.h:3816
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
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
In fs/ext4/inode.c (ffffffff815b4b47)
Location: fs/ext4/ext4.h:3788
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
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
In fs/ext4/inode.c (ffffffff815ed9a7)
Location: fs/ext4/ext4.h:3804
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_one_extent
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
In fs/ext4/inode.c (ffff8000104848bc)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (c0645e9c)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (c0000000005aa4a8)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffe00030cc5a)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff813a8396)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff81398e26)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff813a5bf6)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
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
In fs/ext4/inode.c (ffffffff813ba356)
Location: fs/ext4/ext4.h:3384
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
</details>
</li>
</ul>

## Differences
