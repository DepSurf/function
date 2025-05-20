# Function: <code>io_kill_timeout</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8134482b)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81341480-ffffffff813414dc: io_kill_timeout.part.0 (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81385469)
Location: fs/io_uring.c:1130
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81381d90-ffffffff81381de2: io_kill_timeout.part.0 (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81390a11)
Location: fs/io_uring.c:1597
Inline: True
Inline callers:
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_kill_timeouts
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
In fs/io_uring.c (ffffffff81397182)
Location: fs/io_uring.c:1304
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_kill_timeouts
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
In fs/io_uring.c (ffffffff813e5d58)
Location: fs/io_uring.c:1514
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_commit_cqring_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_kill_timeout(struct io_kiocb *req, int status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8fa9f)
Location: io_uring/io_uring.c:1888
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_kill_timeouts
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff81e8fa9f-ffffffff81e8fb42: io_kill_timeout (STB_LOCAL)
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
In io_uring/timeout.c (ffffffff81799f39)
Location: io_uring/timeout.c:52
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/timeout.c (ffffffff817daffc)
Location: io_uring/timeout.c:92
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
Direct callers:
  - io_uring/timeout.c:io_kill_timeouts
```
**Symbols:**

```
ffffffff817d9f00-ffffffff817d9f86: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/timeout.c (ffffffff8181f2ec)
Location: io_uring/timeout.c:92
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
Direct callers:
  - io_uring/timeout.c:io_kill_timeouts
```
**Symbols:**

```
ffffffff8181e1f0-ffffffff8181e276: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffff800010402bb8)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffff800010401520-ffff8000104015a0: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (c05d60bc)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
c05d34b4-c05d3534: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (c00000000050f460)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
c00000000050b100-c00000000050b1a4: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffe0002b03d8)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffe0002ad808-ffffffe0002ad860: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8133ce0b)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81339a60-ffffffff81339abc: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8132dadb)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff8132a790-ffffffff8132a7ec: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8133a8db)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81337530-ffffffff8133758c: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8134da9b)
Location: fs/io_uring.c:507
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff8134a8b0-ffffffff8134a90c: io_kill_timeout.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
