# Function: <code>pipe_buf_confirm</code>

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
In fs/pipe.c (ffffffff8124ed51)
Location: include/linux/pipe_fs_i.h:143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8127a50e)
Location: include/linux/pipe_fs_i.h:143
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81358a11)
Location: include/linux/pipe_fs_i.h:143
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/pipe.c (ffffffff8125ac4b)
Location: include/linux/pipe_fs_i.h:143
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812879c5)
Location: include/linux/pipe_fs_i.h:143
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff8136d35a)
Location: include/linux/pipe_fs_i.h:143
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/pipe.c (ffffffff8127cfe3)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812aa4ed)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81391dd8)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/pipe.c (ffffffff812a3f39)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812d1be5)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff813c0e22)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812b9085)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff812e6fc5)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff813da182)
Location: include/linux/pipe_fs_i.h:144
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812d5cb2)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff813042c3)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81405dc4)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812e7822)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81317343)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81420924)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff8131f84b)
Location: include/linux/pipe_fs_i.h:209
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81351922)
Location: include/linux/pipe_fs_i.h:209
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe_feed
```
```
In fs/fuse/dev.c (ffffffff8146f960)
Location: include/linux/pipe_fs_i.h:209
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff8132ad88)
Location: include/linux/pipe_fs_i.h:209
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8135e73d)
Location: include/linux/pipe_fs_i.h:209
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:splice_from_pipe_feed
```
```
In fs/fuse/dev.c (ffffffff8148a1a4)
Location: include/linux/pipe_fs_i.h:209
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff81330d55)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff813647c7)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff8148fcfc)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff8137e4d5)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff813b35b7)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff814e776c)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff813fde6d)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8143870e)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81575aad)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff81487a8d)
Location: include/linux/pipe_fs_i.h:191
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814c61cf)
Location: include/linux/pipe_fs_i.h:191
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff8161ae30)
Location: include/linux/pipe_fs_i.h:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff814bc942)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff814fcdb3)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81652fa0)
Location: include/linux/pipe_fs_i.h:211
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff814eed7e)
Location: include/linux/pipe_fs_i.h:227
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff815319e3)
Location: include/linux/pipe_fs_i.h:227
Inline: True
Inline callers:
  - fs/splice.c:splice_to_socket
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff8168c5b0)
Location: include/linux/pipe_fs_i.h:227
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffff800010390564)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffff8000103cf6f0)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffff800010503508)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (c05770c4)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (c05aa7e0)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (c06bfb98)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (c0000000004880d0)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (c0000000004d00a4)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (c000000000647ff4)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffe00025feac)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffe00028b89a)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffe000370378)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812dfe02)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8130f923)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81418f04)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812d0a42)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff81300533)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff81409984)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812ddc12)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8130d713)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff814150a4)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/pipe.c (ffffffff812eeb92)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
```
```
In fs/splice.c (ffffffff8131ef13)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
  - fs/splice.c:__splice_from_pipe
```
```
In fs/fuse/dev.c (ffffffff8142be21)
Location: include/linux/pipe_fs_i.h:139
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
</details>
</li>
</ul>

## Differences
