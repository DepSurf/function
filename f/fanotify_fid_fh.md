# Function: <code>fanotify_fid_fh</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8131d857)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e0d1)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81330697)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81330f11)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
</details>
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
In fs/notify/fanotify/fanotify.c (ffff8000103ed87c)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee2d4)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (c05c40d8)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (c05c5490)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
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
In fs/notify/fanotify/fanotify.c (c0000000004f5040)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (c0000000004f603c)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffe0002a129c)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a179a)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81328c77)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813294f1)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81319817)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a091)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81326747)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81326fc1)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81338567)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81338eb1)
Location: fs/notify/fanotify/fanotify.h:40
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_to_user
```
</details>
</li>
</ul>

## Differences
