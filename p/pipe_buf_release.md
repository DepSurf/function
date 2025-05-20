# Function: <code>pipe_buf_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124f2b2)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812797e7)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8135a489)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff81460cc1)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff8125b210)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81286d45)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8136f6cf)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff81466048)
Location: include/linux/pipe_fs_i.h:129
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff8127d5d0)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812a9538)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff813942f4)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff81492148)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812a4562)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812d009d)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff813c3336)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff814c6de0)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812b96c2)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812e54d1)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff813dcbcc)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff814db959)
Location: include/linux/pipe_fs_i.h:130
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812d6312)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81303caf)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8140875d)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff81507291)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812e7e82)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81316d30)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff814229dd)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff815253a1)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff8131fe07)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8135209a)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe_feed
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81471bc2)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff8158a9e8)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff8132b347)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8135d11a)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe_feed
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8148c432)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff815a5e8c)
Location: include/linux/pipe_fs_i.h:195
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff81331267)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81363bc0)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81491d35)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff815b1ac7)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff8137e9da)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff813b23b0)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff814e982e)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In lib/iov_iter.c (ffffffff816159b5)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff813fea74)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814373ca)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8157800e)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In lib/iov_iter.c (ffffffff816e259c)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:copy_mc_pipe_to_iter
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
In fs/pipe.c (ffffffff81488784)
Location: include/linux/pipe_fs_i.h:177
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814c54b7)
Location: include/linux/pipe_fs_i.h:177
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:generic_file_splice_read
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8161d53e)
Location: include/linux/pipe_fs_i.h:177
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In lib/iov_iter.c (ffffffff817d23cd)
Location: include/linux/pipe_fs_i.h:177
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff814bd697)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814fac72)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8165567e)
Location: include/linux/pipe_fs_i.h:197
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_try_move_page
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
In fs/pipe.c (ffffffff814efb37)
Location: include/linux/pipe_fs_i.h:213
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8152f762)
Location: include/linux/pipe_fs_i.h:213
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:splice_from_pipe_next
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8168e3ee)
Location: include/linux/pipe_fs_i.h:213
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
  - fs/fuse/dev.c:fuse_try_move_page
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
In fs/pipe.c (ffff800010390c10)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffff8000103cd6e0)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffff800010505768)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffff80001062f7ac)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (c05776fc)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (c05a9244)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (c06c1b7c)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (c07d6198)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (c000000000488ac0)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (c0000000004cf5f8)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (c00000000064ad30)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (c0000000007d3664)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffe0002603d4)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffe00028a9c2)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffe000372104)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffe00045ebda)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812e0462)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8130f310)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8141afbd)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff8151d981)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812d10a2)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812fff20)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8140ba3d)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff8150dc71)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812de272)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8130d100)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8141715d)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff81519a11)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
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
In fs/pipe.c (ffffffff812ef1f2)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/pipe.c:free_pipe_info
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8131e8f0)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/splice.c:splice_direct_to_actor
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
  - fs/splice.c:add_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8142deed)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
```
In lib/iov_iter.c (ffffffff81533221)
Location: include/linux/pipe_fs_i.h:125
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_advance
```
</details>
</li>
</ul>

## Differences
