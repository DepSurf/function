# Function: <code>fanotify_fh_buf</code>

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
In fs/notify/fanotify/fanotify.c (ffffffff8136a555)
Location: fs/notify/fanotify/fanotify.h:50
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b52c)
Location: fs/notify/fanotify/fanotify.h:50
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff8137769d)
Location: fs/notify/fanotify/fanotify.h:71
Inline: True
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137859f)
Location: fs/notify/fanotify/fanotify.h:71
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff8137dfa3)
Location: fs/notify/fanotify/fanotify.h:72
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f1bf)
Location: fs/notify/fanotify/fanotify.h:72
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff813caee3)
Location: fs/notify/fanotify/fanotify.h:72
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc16f)
Location: fs/notify/fanotify/fanotify.h:72
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81452d6b)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454961)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff814e1a5a)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3851)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81518319)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a106)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff8154c6f9)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e4d6)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_fid_info_to_user
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
