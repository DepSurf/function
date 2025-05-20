# Function: <code>percpu_rwsem_release</code>

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
In fs/super.c (ffffffff8120ef10)
Location: include/linux/percpu-rwsem.h:39
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff81235940)
Location: include/linux/percpu-rwsem.h:39
Inline: True
Inline callers:
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
  - fs/super.c:freeze_super
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
In fs/super.c (ffffffff812486ac)
Location: include/linux/percpu-rwsem.h:129
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:129
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
In fs/super.c (ffffffff81253fc6)
Location: include/linux/percpu-rwsem.h:129
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:129
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
In fs/super.c (ffffffff812760d9)
Location: include/linux/percpu-rwsem.h:130
Inline: True
Inline callers:
  - fs/super.c:thaw_super
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:130
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
In fs/super.c (ffffffff8129e381)
Location: include/linux/percpu-rwsem.h:130
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:130
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
In fs/super.c (ffffffff812b3351)
Location: include/linux/percpu-rwsem.h:130
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:130
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
In fs/super.c (ffffffff812cffbc)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (ffffffff812e1b6d)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:141
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
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:141
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
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:141
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
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:141
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
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:141
Inline: True
```
```
In io_uring/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:141
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
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/percpu-rwsem.h:147
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
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
```
In io_uring/rw.c (0)
Location: include/linux/percpu-rwsem.h:147
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
Location: include/linux/percpu-rwsem.h:147
Inline: True
```
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
In io_uring/rw.c (0)
Location: include/linux/percpu-rwsem.h:147
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
In fs/super.c (ffff800010386c5c)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (c056f4dc)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (c00000000047ccb0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (ffffffff812da14d)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (ffffffff812cadcd)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (ffffffff812d7f5d)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
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
In fs/super.c (ffffffff812e8db5)
Location: include/linux/percpu-rwsem.h:118
Inline: True
Inline callers:
  - fs/super.c:thaw_super_locked
  - fs/super.c:freeze_super
```
```
In fs/aio.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
```
In fs/io_uring.c (0)
Location: include/linux/percpu-rwsem.h:118
Inline: True
```
</details>
</li>
</ul>

## Differences
