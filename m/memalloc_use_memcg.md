# Function: <code>memalloc_use_memcg</code>

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
In fs/buffer.c (ffffffff812ebe2a)
Location: include/linux/sched/mm.h:262
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb707)
Location: include/linux/sched/mm.h:262
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcb16)
Location: include/linux/sched/mm.h:262
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
In fs/buffer.c (ffffffff8130d549)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131c01c)
Location: include/linux/sched/mm.h:319
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d5c3)
Location: include/linux/sched/mm.h:319
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
In fs/buffer.c (ffffffff81320519)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132edfc)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81330403)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (ffffffff81359979)
Location: include/linux/sched/mm.h:323
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368ce6)
Location: include/linux/sched/mm.h:323
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a9ad)
Location: include/linux/sched/mm.h:323
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
In fs/buffer.c (ffff8000103d91a8)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eb97c)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed67c)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (c05b1f0c)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (c05c285c)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (c05c3e54)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (c0000000004dd1a4)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2e04)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4d48)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (ffffffe000291d04)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fc12)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a10a4)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (ffffffff81318af9)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813273dc)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813289e3)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (ffffffff813096e9)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81317f7c)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319583)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (ffffffff813165c9)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324eac)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813264b3)
Location: include/linux/sched/mm.h:321
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
In fs/buffer.c (ffffffff813283b9)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/buffer.c:alloc_page_buffers
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336c8c)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813382d3)
Location: include/linux/sched/mm.h:321
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
</ul>

## Differences
