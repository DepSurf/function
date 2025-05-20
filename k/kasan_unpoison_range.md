# Function: <code>kasan_unpoison_range</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: include/linux/kasan.h:263
Inline: True
```
```
In mm/mempool.c (ffffffff8125f10e)
Location: include/linux/kasan.h:263
Inline: True
Inline callers:
  - mm/mempool.c:mempool_exit
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:263
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
In kernel/fork.c (0)
Location: include/linux/kasan.h:300
Inline: True
```
```
In mm/mempool.c (ffffffff81263c7e)
Location: include/linux/kasan.h:300
Inline: True
Inline callers:
  - mm/mempool.c:mempool_exit
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:300
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
In kernel/fork.c (0)
Location: include/linux/kasan.h:310
Inline: True
```
```
In mm/mempool.c (ffffffff812a015f)
Location: include/linux/kasan.h:310
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_exit
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:310
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
In kernel/fork.c (0)
Location: include/linux/kasan.h:276
Inline: True
```
```
In mm/mempool.c (ffffffff812f7742)
Location: include/linux/kasan.h:276
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_exit
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:276
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
In kernel/fork.c (0)
Location: include/linux/kasan.h:249
Inline: True
```
```
In mm/mempool.c (ffffffff81361083)
Location: include/linux/kasan.h:249
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_exit
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:249
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
In kernel/fork.c (0)
Location: include/linux/kasan.h:234
Inline: True
```
```
In mm/mempool.c (ffffffff81393443)
Location: include/linux/kasan.h:234
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc
  - mm/mempool.c:mempool_resize
  - mm/mempool.c:mempool_exit
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:234
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/kasan.h:234
Inline: True
```
```
In io_uring/net.c (0)
Location: include/linux/kasan.h:234
Inline: True
```
```
In io_uring/poll.c (0)
Location: include/linux/kasan.h:234
Inline: True
```
```
In io_uring/rsrc.c (0)
Location: include/linux/kasan.h:234
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
In kernel/fork.c (0)
Location: include/linux/kasan.h:356
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/kasan.h:356
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
