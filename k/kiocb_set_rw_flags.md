# Function: <code>kiocb_set_rw_flags</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124f91b)
Location: include/linux/fs.h:3162
Inline: True
```
```
In fs/aio.c (ffffffff812a749a)
Location: include/linux/fs.h:3162
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
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
In fs/read_write.c (ffffffff8127185b)
Location: include/linux/fs.h:3242
Inline: True
```
```
In fs/aio.c (ffffffff812ca82f)
Location: include/linux/fs.h:3242
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
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
In fs/read_write.c (ffffffff812976e7)
Location: include/linux/fs.h:3267
Inline: True
```
```
In fs/aio.c (ffffffff812f2739)
Location: include/linux/fs.h:3267
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
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
In fs/read_write.c (ffffffff812ac3a6)
Location: include/linux/fs.h:3346
Inline: True
```
```
In fs/aio.c (ffffffff81307137)
Location: include/linux/fs.h:3346
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
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
In fs/read_write.c (ffffffff812c8aa2)
Location: include/linux/fs.h:3357
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81328707)
Location: include/linux/fs.h:3357
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8132d6dd)
Location: include/linux/fs.h:3357
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff812da4b2)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff8133b4b7)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8134077c)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff813108fe)
Location: include/linux/fs.h:3469
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81375081)
Location: include/linux/fs.h:3469
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8137b327)
Location: include/linux/fs.h:3469
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff8131d311)
Location: include/linux/fs.h:3262
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81382f51)
Location: include/linux/fs.h:3262
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81389fa1)
Location: include/linux/fs.h:3262
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff81323481)
Location: include/linux/fs.h:3514
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81389fc1)
Location: include/linux/fs.h:3514
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813910ea)
Location: include/linux/fs.h:3514
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff81370974)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff813d72a4)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813e2e9a)
Location: include/linux/fs.h:3494
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff813ef4fb)
Location: include/linux/fs.h:3272
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81460e9f)
Location: include/linux/fs.h:3272
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In io_uring/io_uring.c (ffffffff816c74ff)
Location: include/linux/fs.h:3272
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rw_init_file
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
In fs/read_write.c (ffffffff8147762a)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff814f0e1f)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In io_uring/rw.c (ffffffff817a3400)
Location: include/linux/fs.h:3414
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_init_file
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
In fs/read_write.c (ffffffff814abfaa)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81527c2f)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In io_uring/rw.c (ffffffff817e43a0)
Location: include/linux/fs.h:3029
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_init_file
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
In fs/read_write.c (ffffffff814dd3b9)
Location: include/linux/fs.h:3326
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff8155ca27)
Location: include/linux/fs.h:3326
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In io_uring/rw.c (ffffffff81828470)
Location: include/linux/fs.h:3326
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_init_file
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
In fs/read_write.c (ffff80001037f7d0)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffff8000103fa160)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffff8000104006f0)
Location: include/linux/fs.h:3419
Inline: True
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
In fs/read_write.c (c0569e3c)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (c05ce334)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c05d2118)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (c0000000004758e4)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (c0000000005037e0)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (c000000000509f88)
Location: include/linux/fs.h:3419
Inline: True
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
In fs/read_write.c (ffffffe00025548c)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffe0002a9af8)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffe0002ace22)
Location: include/linux/fs.h:3419
Inline: True
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
In fs/read_write.c (ffffffff812d2a92)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81333a97)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81338d5c)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff812c3712)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81324707)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff81329a8c)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff812d08a2)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81331567)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff8133682c)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
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
In fs/read_write.c (ffffffff812e16d2)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81344157)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/aio.c:aio_prep_rw
```
```
In fs/io_uring.c (ffffffff813498fc)
Location: include/linux/fs.h:3419
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
</ul>

## Differences
