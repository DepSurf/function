# Function: <code>io_remove_next_linked</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391a25)
Location: fs/io_uring.c:2042
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_kill_linked_timeout
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
In fs/io_uring.c (ffffffff81397737)
Location: fs/io_uring.c:1799
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_disarm_next
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
In fs/io_uring.c (ffffffff813df05b)
Location: fs/io_uring.c:2043
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
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
In io_uring/io_uring.c (ffffffff816ce65b)
Location: io_uring/io_uring.c:2527
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_link_timeout_fn
  - io_uring/io_uring.c:io_disarm_next
  - io_uring/io_uring.c:io_disarm_next
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
In io_uring/timeout.c (ffffffff81798efb)
Location: io_uring/timeout.c:144
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
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
In io_uring/timeout.c (ffffffff817d9dab)
Location: io_uring/timeout.c:184
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
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
In io_uring/timeout.c (ffffffff8181dfbb)
Location: io_uring/timeout.c:184
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
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
