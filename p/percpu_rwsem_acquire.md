# Function: <code>percpu_rwsem_acquire</code>

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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:49
Inline: True
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:49
Inline: True
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:139
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:139
Inline: True
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:139
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:139
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:140
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:140
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
In fs/super.c (ffffffff8129c543)
Location: include/linux/percpu-rwsem.h:140
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:140
Inline: True
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
In fs/super.c (ffffffff812b1683)
Location: include/linux/percpu-rwsem.h:140
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:140
Inline: True
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
In fs/super.c (ffffffff812ce3c3)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
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
In fs/super.c (ffffffff812dfe73)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:147
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:147
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:147
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:147
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:147
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/percpu-rwsem.h:153
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/percpu-rwsem.h:153
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
In fs/read_write.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In fs/backing-file.c (0)
Location: include/linux/percpu-rwsem.h:153
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/percpu-rwsem.h:153
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
In fs/super.c (ffff800010386bac)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
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
In fs/super.c (c056f448)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
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
In fs/super.c (c00000000047cbc0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
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
In fs/super.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
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
In fs/super.c (ffffffff812d8453)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
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
In fs/super.c (ffffffff812c90d3)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
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
In fs/super.c (ffffffff812d6263)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
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
In fs/super.c (ffffffff812e6e23)
Location: include/linux/percpu-rwsem.h:128
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:128
Inline: True
```
</details>
</li>
</ul>

## Differences
