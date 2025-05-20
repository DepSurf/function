# Function: <code>req_need_defer</code>

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
In fs/io_uring.c (ffffffff81386970)
Location: fs/io_uring.c:1028
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff81395c92)
Location: fs/io_uring.c:1344
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff8139e09f)
Location: fs/io_uring.c:1208
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
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
In fs/io_uring.c (ffffffff813ef440)
Location: fs/io_uring.c:1379
Inline: True
Inline callers:
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_commit_cqring_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool req_need_defer(struct io_kiocb *req, u32 seq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8fb42)
Location: io_uring/io_uring.c:1752
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff81e8fb42-ffffffff81e8fb74: req_need_defer (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff817905b7)
Location: io_uring/io_uring.c:357
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/io_uring.c:__io_commit_cqring_flush
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
In io_uring/io_uring.c (ffffffff817cf9a7)
Location: io_uring/io_uring.c:356
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/io_uring.c:__io_commit_cqring_flush
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
In io_uring/io_uring.c (ffffffff81812ad7)
Location: io_uring/io_uring.c:370
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/io_uring.c:__io_commit_cqring_flush
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
