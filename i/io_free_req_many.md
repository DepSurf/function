# Function: <code>io_free_req_many</code>

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
In fs/io_uring.c (ffffffff8132e972)
Location: fs/io_uring.c:601
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (ffffffff81341e5c)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff81384b6d)
Location: fs/io_uring.c:1455
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
Direct callers:
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_iopoll_complete
```
**Symbols:**

```
ffffffff81380ca0-ffffffff81380dee: io_free_req_many.part.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104029b8)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (c05d5a20)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (c00000000050c0f4)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (ffffffe0002ae386)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (ffffffff8133a43c)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (ffffffff8132b14c)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (ffffffff81337f0c)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
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
In fs/io_uring.c (ffffffff8134ce36)
Location: fs/io_uring.c:664
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_iopoll_getevents
```
</details>
</li>
</ul>

## Differences
