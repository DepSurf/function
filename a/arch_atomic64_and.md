# Function: <code>arch_atomic64_and</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee7e6)
Location: arch/x86/include/asm/atomic64_64.h:230
Inline: True
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
In kernel/locking/mutex.c (ffffffff81a29a46)
Location: arch/x86/include/asm/atomic64_64.h:194
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
In kernel/locking/mutex.c (ffffffff81a9a100)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810f7f3c)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/mutex.c (ffffffff81ad1a50)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff81103d6c)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/mutex.c (ffffffff81bc9b6d)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110e964)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/mutex.c (ffffffff81c429cd)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110bd24)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff8160a6dd)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
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
In kernel/locking/mutex.c (ffffffff81c345fa)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8110d904)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff815ed331)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_resize
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
In kernel/locking/mutex.c (ffffffff81d52f72)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8112d1fc)
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff8165a49e)
Location: arch/x86/include/asm/atomic64_64.h:200
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
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8114e533)
Location: arch/x86/include/asm/atomic64_64.h:200
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
Location: arch/x86/include/asm/atomic64_64.h:200
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
Location: arch/x86/include/asm/atomic64_64.h:200
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8117d52b)
Location: arch/x86/include/asm/atomic64_64.h:200
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
Location: arch/x86/include/asm/atomic64_64.h:200
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
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff821533ab)
Location: arch/x86/include/asm/atomic64_64.h:119
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8118e20b)
Location: arch/x86/include/asm/atomic64_64.h:119
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff818e6881)
Location: arch/x86/include/asm/atomic64_64.h:119
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_find_bit
  - lib/sbitmap.c:sbitmap_resize
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
In kernel/locking/mutex.c (ffffffff822361eb)
Location: arch/x86/include/asm/atomic64_64.h:119
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff8119cbbb)
Location: arch/x86/include/asm/atomic64_64.h:119
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In lib/sbitmap.c (ffffffff8192d8a1)
Location: arch/x86/include/asm/atomic64_64.h:119
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:sbitmap_queue_clear_batch
  - lib/sbitmap.c:__sbitmap_queue_get_batch
  - lib/sbitmap.c:sbitmap_find_bit
  - lib/sbitmap.c:sbitmap_resize
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a708c0)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810fd07c)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/mutex.c (ffffffff81a2ccb0)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810ed28c)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/mutex.c (ffffffff81adccd0)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810fa23c)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/mutex.c (ffffffff81ae8e90)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff811053ac)
Location: arch/x86/include/asm/atomic64_64.h:194
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
</ul>

## Differences
