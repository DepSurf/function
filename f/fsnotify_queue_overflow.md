# Function: <code>fsnotify_queue_overflow</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812e6c4f)
Location: include/linux/fsnotify_backend.h:378
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812e82c3)
Location: include/linux/fsnotify_backend.h:378
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb821)
Location: include/linux/fsnotify_backend.h:408
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff812fcf9c)
Location: include/linux/fsnotify_backend.h:408
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131c16c)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131dbfa)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132ef50)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81330a3a)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368e4a)
Location: include/linux/fsnotify_backend.h:443
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136ae75)
Location: include/linux/fsnotify_backend.h:443
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81376181)
Location: include/linux/fsnotify_backend.h:492
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137843d)
Location: include/linux/fsnotify_backend.h:492
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8137cb1a)
Location: include/linux/fsnotify_backend.h:492
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137f053)
Location: include/linux/fsnotify_backend.h:492
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813c9a1a)
Location: include/linux/fsnotify_backend.h:492
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cc005)
Location: include/linux/fsnotify_backend.h:492
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814514ac)
Location: include/linux/fsnotify_backend.h:630
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8145462e)
Location: include/linux/fsnotify_backend.h:630
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814dff98)
Location: include/linux/fsnotify_backend.h:631
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e34ea)
Location: include/linux/fsnotify_backend.h:631
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff815168e1)
Location: include/linux/fsnotify_backend.h:631
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519e15)
Location: include/linux/fsnotify_backend.h:631
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8154acd1)
Location: include/linux/fsnotify_backend.h:631
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154e1ef)
Location: include/linux/fsnotify_backend.h:631
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103ebab8)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103edc10)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (c05c29c8)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (c05c44a8)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2fe0)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f55a0)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fd4e)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a157a)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81327530)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8132901a)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813180d0)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319bba)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81325000)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81326aea)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336de0)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81338905)
Location: include/linux/fsnotify_backend.h:416
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
</ul>

## Differences
