# Function: <code>wait_on_bit_io</code>

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
In fs/buffer.c (ffffffff81243a7d)
Location: include/linux/wait.h:1010
Inline: True
Inline callers:
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff812e8699)
Location: include/linux/wait.h:1010
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8126eb1a)
Location: include/linux/wait.h:1074
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81316298)
Location: include/linux/wait.h:1074
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81281d31)
Location: include/linux/wait.h:1065
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff8132c288)
Location: include/linux/wait.h:1065
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8128f48a)
Location: include/linux/wait_bit.h:100
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813414f1)
Location: include/linux/wait_bit.h:100
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff812b20bf)
Location: include/linux/wait_bit.h:104
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81365b23)
Location: include/linux/wait_bit.h:104
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff812da02b)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81394307)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff812ef519)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813ad057)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81310d62)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813d72d6)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81323d49)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813f138c)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8135d8aa)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff8143e84e)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8136b49a)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff8145aabe)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81371d3a)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff81460352)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff813c0d5a)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff814b57d5)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81444800)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff8153f159)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff814d3091)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff815ddb46)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81509cb1)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff816155ca)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8153eae1)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (ffffffff8164e3b7)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffff8000103dd0e0)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffff8000104cb2ac)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (c05b65e4)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
```
```
In fs/jbd2/transaction.c (c068ecbc)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (c0000000004e3d70)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (c000000000604404)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffe00029525c)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffe00034418c)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8131c329)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813e996c)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8130cec9)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813da3ec)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff81319df9)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813e6cec)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
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
In fs/buffer.c (ffffffff8132bad6)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813fc2c1)
Location: include/linux/wait_bit.h:96
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:do_get_write_access
```
</details>
</li>
</ul>

## Differences
