# Function: <code>fsnotify_data_path</code>

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
In fs/notify/fsnotify.c (ffffffff813663fc)
Location: include/linux/fsnotify_backend.h:236
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368c65)
Location: include/linux/fsnotify_backend.h:236
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136ab72)
Location: include/linux/fsnotify_backend.h:236
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_group_event_mask
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
In fs/notify/fsnotify.c (ffffffff81373494)
Location: include/linux/fsnotify_backend.h:268
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81378192)
Location: include/linux/fsnotify_backend.h:268
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fsnotify.c (ffffffff81379d7a)
Location: include/linux/fsnotify_backend.h:265
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137ed51)
Location: include/linux/fsnotify_backend.h:265
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fsnotify.c (ffffffff813c696a)
Location: include/linux/fsnotify_backend.h:265
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb735)
Location: include/linux/fsnotify_backend.h:265
Inline: True
Inline callers:
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
In fs/notify/fsnotify.c (ffffffff8144da19)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453035)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
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
In fs/notify/fsnotify.c (ffffffff814dc0d9)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e1de5)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
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
In fs/notify/fsnotify.c (ffffffff815128c9)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815186a5)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
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
In fs/notify/fsnotify.c (ffffffff81546d79)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:__fsnotify_parent
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154ca85)
Location: include/linux/fsnotify_backend.h:329
Inline: True
Inline callers:
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
