# Function: <code>FANOTIFY_PERM</code>

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
In fs/notify/fanotify/fanotify.c (ffffffff8136a356)
Location: fs/notify/fanotify/fanotify.h:174
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136be7c)
Location: fs/notify/fanotify/fanotify.h:174
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:get_one_event
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
In fs/notify/fanotify/fanotify.c (ffffffff813774ab)
Location: fs/notify/fanotify/fanotify.h:256
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137971c)
Location: fs/notify/fanotify/fanotify.h:256
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:get_one_event
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
In fs/notify/fanotify/fanotify.c (ffffffff8137dd56)
Location: fs/notify/fanotify/fanotify.h:274
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380289)
Location: fs/notify/fanotify/fanotify.h:274
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff813cac96)
Location: fs/notify/fanotify/fanotify.h:274
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd99e)
Location: fs/notify/fanotify/fanotify.h:274
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:434
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:434
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:434
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:434
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:438
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:438
Inline: True
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.h:438
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:438
Inline: True
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
