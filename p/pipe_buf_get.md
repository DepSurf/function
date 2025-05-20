# Function: <code>pipe_buf_get</code>

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
In fs/splice.c (ffffffff8127b521)
Location: include/linux/pipe_fs_i.h:118
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
```
In fs/fuse/dev.c (ffffffff8135a38d)
Location: include/linux/pipe_fs_i.h:118
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff812888ff)
Location: include/linux/pipe_fs_i.h:118
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
```
In fs/fuse/dev.c (ffffffff8136f58f)
Location: include/linux/pipe_fs_i.h:118
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff812ab42f)
Location: include/linux/pipe_fs_i.h:119
Inline: True
Inline callers:
  - fs/splice.c:SyS_tee
  - fs/splice.c:SyS_splice
```
```
In fs/fuse/dev.c (ffffffff813941af)
Location: include/linux/pipe_fs_i.h:119
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff812d102a)
Location: include/linux/pipe_fs_i.h:119
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff813c3274)
Location: include/linux/pipe_fs_i.h:119
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff812e625a)
Location: include/linux/pipe_fs_i.h:119
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff813dcb06)
Location: include/linux/pipe_fs_i.h:119
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff81304e81)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff81408689)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff81317f11)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff81422909)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff813510a0)
Location: include/linux/pipe_fs_i.h:184
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81471a76)
Location: include/linux/pipe_fs_i.h:184
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff8135e310)
Location: include/linux/pipe_fs_i.h:184
Inline: True
Inline callers:
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8148c2e6)
Location: include/linux/pipe_fs_i.h:184
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff81365c8f)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81491be9)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff813b457f)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff814e96d9)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff8143994e)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff81577e71)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff814c7c7e)
Location: include/linux/pipe_fs_i.h:166
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8161d3a1)
Location: include/linux/pipe_fs_i.h:166
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff814fdcef)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff816554ec)
Location: include/linux/pipe_fs_i.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff815328dc)
Location: include/linux/pipe_fs_i.h:202
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:splice_pipe_to_pipe
```
```
In fs/fuse/dev.c (ffffffff8168e25c)
Location: include/linux/pipe_fs_i.h:202
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffff8000103ce028)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:__arm64_sys_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffff800010505694)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (c05ab164)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (c06c1a8c)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (c0000000004d1254)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (c00000000064ac0c)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffe00028c140)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:__se_sys_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffe00037202c)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff813104f1)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff8141aee9)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff81301101)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff8140b969)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff8130e2e1)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff81417089)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
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
In fs/splice.c (ffffffff8131fae1)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/splice.c:do_tee
  - fs/splice.c:do_splice
```
```
In fs/fuse/dev.c (ffffffff8142de19)
Location: include/linux/pipe_fs_i.h:114
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_splice_write
```
</details>
</li>
</ul>

## Differences
