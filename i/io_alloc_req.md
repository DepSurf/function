# Function: <code>io_alloc_req</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388abe)
Location: fs/io_uring.c:1367
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff8139974b)
Location: fs/io_uring.c:1973
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff813a0a59)
Location: fs/io_uring.c:1720
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff813efa4e)
Location: fs/io_uring.c:1972
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff816d6186)
Location: io_uring/io_uring.c:2489
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff8178b813)
Location: io_uring/io_uring.h:392
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_caches_free
  - io_uring/io_uring.c:io_submit_sqes
```
```
In io_uring/notif.c (ffffffff817a52bc)
Location: io_uring/io_uring.h:392
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
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
In io_uring/io_uring.c (ffffffff817d2893)
Location: io_uring/io_uring.h:361
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
```
```
In io_uring/notif.c (ffffffff817e6275)
Location: io_uring/io_uring.h:361
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
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
In io_uring/io_uring.c (ffffffff81815bb3)
Location: io_uring/io_uring.h:363
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
```
```
In io_uring/notif.c (ffffffff8182a495)
Location: io_uring/io_uring.h:363
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
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
