# Function: <code>fsnotify_data_inode</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81191e24)
Location: include/linux/fsnotify_backend.h:223
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff811924cf)
Location: include/linux/fsnotify_backend.h:223
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136a97a)
Location: include/linux/fsnotify_backend.h:223
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff81373ba2)
Location: include/linux/fsnotify_backend.h:256
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377b8e)
Location: include/linux/fsnotify_backend.h:256
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff8137a587)
Location: include/linux/fsnotify_backend.h:253
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e628)
Location: include/linux/fsnotify_backend.h:253
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff813c7207)
Location: include/linux/fsnotify_backend.h:253
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb708)
Location: include/linux/fsnotify_backend.h:253
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff8144e59e)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453c96)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff814dccae)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2b46)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff815134fa)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519423)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
In fs/notify/fsnotify.c (ffffffff8154798a)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154d803)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
