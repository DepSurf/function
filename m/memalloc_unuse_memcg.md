# Function: <code>memalloc_unuse_memcg</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ebeb7)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb735)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcbbc)
Location: include/linux/sched/mm.h:274
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff8130d5ed)
Location: include/linux/sched/mm.h:331
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131c055)
Location: include/linux/sched/mm.h:331
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d6d6)
Location: include/linux/sched/mm.h:331
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff813205bd)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132ee35)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81330516)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff81359a1a)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368d3f)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136ab39)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9240)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eb9a0)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed748)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (c05b1f9c)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (c05c2884)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (c05c3f18)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (c0000000004dd240)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2e28)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4e5c)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffe000291d9e)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fc3e)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a1170)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff81318b9d)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81327415)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328af6)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff8130978d)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81317fb5)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319696)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff8131666d)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324ee5)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813265c6)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/buffer.c (ffffffff8132845d)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336cc5)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813383e6)
Location: include/linux/sched/mm.h:333
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
</ul>

## Differences
