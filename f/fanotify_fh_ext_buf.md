# Function: <code>fanotify_fh_ext_buf</code>

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
In fs/notify/fanotify/fanotify.c (ffffffff8136a3cc)
Location: fs/notify/fanotify/fanotify.h:45
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b532)
Location: fs/notify/fanotify/fanotify.h:45
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
In fs/notify/fanotify/fanotify.c (ffffffff813774d2)
Location: fs/notify/fanotify/fanotify.h:66
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813785ac)
Location: fs/notify/fanotify/fanotify.h:66
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
In fs/notify/fanotify/fanotify.c (ffffffff8137dd73)
Location: fs/notify/fanotify/fanotify.h:67
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f1cc)
Location: fs/notify/fanotify/fanotify.h:67
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
In fs/notify/fanotify/fanotify.c (ffffffff813cacb3)
Location: fs/notify/fanotify/fanotify.h:67
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc17c)
Location: fs/notify/fanotify/fanotify.h:67
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
In fs/notify/fanotify/fanotify.c (ffffffff81452a25)
Location: fs/notify/fanotify/fanotify.h:97
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145496c)
Location: fs/notify/fanotify/fanotify.h:97
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
In fs/notify/fanotify/fanotify.c (ffffffff814e16c5)
Location: fs/notify/fanotify/fanotify.h:97
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e385c)
Location: fs/notify/fanotify/fanotify.h:97
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
In fs/notify/fanotify/fanotify.c (ffffffff81517f89)
Location: fs/notify/fanotify/fanotify.h:97
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a111)
Location: fs/notify/fanotify/fanotify.h:97
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
In fs/notify/fanotify/fanotify.c (ffffffff8154c369)
Location: fs/notify/fanotify/fanotify.h:97
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
  - fs/notify/fanotify/fanotify.c:fanotify_fh_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e4e1)
Location: fs/notify/fanotify/fanotify.h:97
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
