# Function: <code>io_iopoll_complete</code>

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
In fs/io_uring.c (0)
Location: fs/io_uring.c:692
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_iopoll_complete(struct io_ring_ctx *ctx, unsigned int *nr_events, struct list_head *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81384a20)
Location: fs/io_uring.c:1797
Inline: False
Direct callers:
  - fs/io_uring.c:io_do_iopoll
```
**Symbols:**

```
ffffffff81384a20-ffffffff81384d66: io_iopoll_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_iopoll_complete(struct io_ring_ctx *ctx, unsigned int *nr_events, struct list_head *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396050)
Location: fs/io_uring.c:2447
Inline: False
Direct callers:
  - fs/io_uring.c:io_do_iopoll
```
**Symbols:**

```
ffffffff81396050-ffffffff81396337: io_iopoll_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_iopoll_complete(struct io_ring_ctx *ctx, unsigned int *nr_events, struct list_head *done, bool resubmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399340)
Location: fs/io_uring.c:2269
Inline: False
Direct callers:
  - fs/io_uring.c:io_do_iopoll
```
**Symbols:**

```
ffffffff81399340-ffffffff813997ad: io_iopoll_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_iopoll_complete(struct io_ring_ctx *ctx, unsigned int *nr_events, struct list_head *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e84b0)
Location: fs/io_uring.c:2481
Inline: False
Direct callers:
  - fs/io_uring.c:io_do_iopoll
```
**Symbols:**

```
ffffffff813e84b0-ffffffff813e88a5: io_iopoll_complete (STB_LOCAL)
```
</details>
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (ffffffe0002ae24c)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
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
In fs/io_uring.c (0)
Location: fs/io_uring.c:763
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool resubmit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool resubmit</code>
</li>
</ul>
</details>
</li>
</ul>
