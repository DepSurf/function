# Function: <code>fsnotify_iter_vfsmount_mark</code>

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
In fs/notify/dnotify/dnotify.c (ffffffff812e6576)
Location: include/linux/fsnotify_backend.h:248
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812e6b0f)
Location: include/linux/fsnotify_backend.h:248
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
In fs/notify/dnotify/dnotify.c (ffffffff812fb106)
Location: include/linux/fsnotify_backend.h:269
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb69f)
Location: include/linux/fsnotify_backend.h:269
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
In fs/notify/dnotify/dnotify.c (ffffffff8131b9dc)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131bfc8)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffff8132e79c)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132eda8)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffff81368678)
Location: include/linux/fsnotify_backend.h:300
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368ca0)
Location: include/linux/fsnotify_backend.h:300
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
In fs/notify/fsnotify.c (ffffffff8137339d)
Location: include/linux/fsnotify_backend.h:335
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
In fs/notify/fsnotify.c (ffffffff81379c7d)
Location: include/linux/fsnotify_backend.h:332
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
In fs/notify/fsnotify.c (ffffffff813c67f8)
Location: include/linux/fsnotify_backend.h:332
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
In fs/notify/fsnotify.c (ffffffff8144d818)
Location: include/linux/fsnotify_backend.h:448
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
In fs/notify/fsnotify.c (ffffffff814dbe68)
Location: include/linux/fsnotify_backend.h:448
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
In fs/notify/fsnotify.c (ffffffff81512643)
Location: include/linux/fsnotify_backend.h:448
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
In fs/notify/fsnotify.c (ffffffff81546af3)
Location: include/linux/fsnotify_backend.h:448
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
In fs/notify/dnotify/dnotify.c (ffff8000103eb11c)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eb940)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (c05c21e8)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (c05c27cc)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (c0000000004f2398)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2da0)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffe00029f578)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fbda)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffff81326d7c)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81327388)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffff8131791c)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81317f28)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffff8132484c)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324e58)
Location: include/linux/fsnotify_backend.h:274
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
In fs/notify/dnotify/dnotify.c (ffffffff813365cc)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/dnotify/dnotify.c:dnotify_handle_event
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336c38)
Location: include/linux/fsnotify_backend.h:274
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
</details>
</li>
</ul>

## Differences
