# Function: <code>io_queue_sqe_fallback</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void io_queue_sqe_fallback(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:8306
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
```
**Symbols:**

```
ffffffff816d54e0-ffffffff816d5553: io_queue_sqe_fallback (STB_LOCAL)
ffffffff81e9193d-ffffffff81e91947: io_queue_sqe_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_queue_sqe_fallback(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817910b0)
Location: io_uring/io_uring.c:2041
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
```
**Symbols:**

```
ffffffff817910b0-ffffffff81791129: io_queue_sqe_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_queue_sqe_fallback(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d1d90)
Location: io_uring/io_uring.c:2066
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
```
**Symbols:**

```
ffffffff817d1d90-ffffffff817d1e09: io_queue_sqe_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_queue_sqe_fallback(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff818150b0)
Location: io_uring/io_uring.c:2094
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_sqes
  - io_uring/io_uring.c:io_submit_fail_init
```
**Symbols:**

```
ffffffff818150b0-ffffffff81815129: io_queue_sqe_fallback (STB_LOCAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
