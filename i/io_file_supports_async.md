# Function: <code>io_file_supports_async</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d5ff)
Location: fs/io_uring.c:991
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134069b)
Location: fs/io_uring.c:1061
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool io_file_supports_async(struct file *file, int rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c250)
Location: fs/io_uring.c:2129
Inline: True
Direct callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff8137c250-ffffffff8137c2be: io_file_supports_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_file_supports_async(struct file *file, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389920)
Location: fs/io_uring.c:2870
Inline: False
Direct callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81389920-ffffffff813899f8: io_file_supports_async (STB_LOCAL)
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
In fs/io_uring.c (ffffffff8139d46c)
Location: fs/io_uring.c:2666
Inline: True
Inline callers:
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010400614)
Location: fs/io_uring.c:1061
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d204c)
Location: fs/io_uring.c:1061
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509e68)
Location: fs/io_uring.c:1061
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002acd64)
Location: fs/io_uring.c:1061
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338c7b)
Location: fs/io_uring.c:1061
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813299ab)
Location: fs/io_uring.c:1061
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133674b)
Location: fs/io_uring.c:1061
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134981b)
Location: fs/io_uring.c:1061
Inline: True
Inline callers:
  - fs/io_uring.c:io_prep_rw
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
