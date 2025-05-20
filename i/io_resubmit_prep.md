# Function: <code>io_resubmit_prep</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool io_resubmit_prep(struct io_kiocb *req, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2669
Inline: False
Direct callers:
  - fs/io_uring.c:io_iopoll_queue
```
**Symbols:**

```
ffffffff8138fdc0-ffffffff8138ff1c: io_resubmit_prep (STB_LOCAL)
ffffffff81beac43-ffffffff81beac5e: io_resubmit_prep.cold (STB_LOCAL)
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
In fs/io_uring.c (ffffffff8139aa7a)
Location: fs/io_uring.c:2450
Inline: True
Inline callers:
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_iopoll
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
In fs/io_uring.c (ffffffff813eb769)
Location: fs/io_uring.c:2651
Inline: True
Inline callers:
  - fs/io_uring.c:kiocb_done
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
In io_uring/io_uring.c (ffffffff816d5371)
Location: io_uring/io_uring.c:3177
Inline: True
Inline callers:
  - io_uring/io_uring.c:kiocb_done
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
In io_uring/rw.c (ffffffff817a3d3c)
Location: io_uring/rw.c:177
Inline: True
Inline callers:
  - io_uring/rw.c:kiocb_done
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
In io_uring/rw.c (ffffffff817e4d9c)
Location: io_uring/rw.c:177
Inline: True
Inline callers:
  - io_uring/rw.c:kiocb_done
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
In io_uring/rw.c (ffffffff818292b1)
Location: io_uring/rw.c:196
Inline: True
Inline callers:
  - io_uring/rw.c:kiocb_done
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
<b>Regular</b>
<ul>
</ul>
