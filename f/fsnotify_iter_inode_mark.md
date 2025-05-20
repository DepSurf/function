# Function: <code>fsnotify_iter_inode_mark</code>

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
In kernel/audit_watch.c (ffffffff81158d81)
Location: include/linux/fsnotify_backend.h:247
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff81159539)
Location: include/linux/fsnotify_backend.h:247
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812e655e)
Location: include/linux/fsnotify_backend.h:247
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812e6b04)
Location: include/linux/fsnotify_backend.h:247
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff81165d21)
Location: include/linux/fsnotify_backend.h:268
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff811664d7)
Location: include/linux/fsnotify_backend.h:268
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff812fb0ee)
Location: include/linux/fsnotify_backend.h:268
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb694)
Location: include/linux/fsnotify_backend.h:268
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff811728a1)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff81173087)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8131b9c1)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131bfbe)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff8117e751)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff8117eef7)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff8132e781)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132ed9e)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff81191e05)
Location: include/linux/fsnotify_backend.h:299
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff811924b5)
Location: include/linux/fsnotify_backend.h:299
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81368645)
Location: include/linux/fsnotify_backend.h:299
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368c92)
Location: include/linux/fsnotify_backend.h:299
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81373374)
Location: include/linux/fsnotify_backend.h:333
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81379c54)
Location: include/linux/fsnotify_backend.h:330
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813c67cf)
Location: include/linux/fsnotify_backend.h:330
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144d7ef)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff814dbe34)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8151261d)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81546acd)
Location: include/linux/fsnotify_backend.h:446
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:send_to_group
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
In kernel/audit_watch.c (ffff8000101f35ac)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffff8000101f3e38)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffff8000103eb100)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eb934)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (c0433aa0)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (c0434244)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (c05c21c4)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (c05c27cc)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (c000000000268140)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (c000000000268e24)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (c0000000004f2370)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2d84)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffe000166a8e)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffe0001671ce)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffe00029f55a)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fbce)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff81176d71)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff81177517)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81326d61)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132737e)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff81169f11)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff8116a6b7)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81317901)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81317f1e)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff81174b41)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff811752e7)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff81324831)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324e4e)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
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
In kernel/audit_watch.c (ffffffff81182421)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
```
In kernel/audit_fsnotify.c (ffffffff81182bc7)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
```
In fs/notify/dnotify/dnotify.c (ffffffff813365b1)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336c2e)
Location: include/linux/fsnotify_backend.h:273
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
</details>
</li>
</ul>

## Differences
