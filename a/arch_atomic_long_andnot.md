# Function: <code>arch_atomic_long_andnot</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d52f72)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8112d1fc)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff8165a49e)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
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
In kernel/locking/mutex.c (ffffffff81f23bb6)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8114e533)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff81773a66)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
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
In kernel/locking/mutex.c (ffffffff820cf083)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8117d52b)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff818a43f6)
Location: include/linux/atomic/atomic-long.h:297
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
