# Function: <code>fsnotify_data_dentry</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144ddb0)
Location: include/linux/fsnotify_backend.h:316
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81453dd1)
Location: include/linux/fsnotify_backend.h:316
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
In fs/notify/fsnotify.c (ffffffff814dc47d)
Location: include/linux/fsnotify_backend.h:316
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2c81)
Location: include/linux/fsnotify_backend.h:316
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
In fs/notify/fsnotify.c (ffffffff81512c6f)
Location: include/linux/fsnotify_backend.h:316
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519a84)
Location: include/linux/fsnotify_backend.h:316
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
In fs/notify/fsnotify.c (ffffffff8154711f)
Location: include/linux/fsnotify_backend.h:316
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:send_to_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154de64)
Location: include/linux/fsnotify_backend.h:316
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
