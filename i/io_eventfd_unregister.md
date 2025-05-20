# Function: <code>io_eventfd_unregister</code>

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
In fs/io_uring.c (ffffffff81331e6d)
Location: fs/io_uring.c:3052
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff81345a2d)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813815bb)
Location: fs/io_uring.c:7430
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
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
In fs/io_uring.c (ffffffff8138f2b9)
Location: fs/io_uring.c:8661
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
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
In fs/io_uring.c (ffffffff8139e6ea)
Location: fs/io_uring.c:8568
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
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
In fs/io_uring.c (ffffffff813eed5c)
Location: fs/io_uring.c:9275
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int io_eventfd_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d880b)
Location: io_uring/io_uring.c:10621
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff816c89d0-ffffffff816c8a1e: io_eventfd_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_eventfd_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81788800)
Location: io_uring/io_uring.c:2673
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81788800-ffffffff8178887d: io_eventfd_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_eventfd_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c8ee0)
Location: io_uring/io_uring.c:2825
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817c8ee0-ffffffff817c8f5d: io_eventfd_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_eventfd_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/register.c (ffffffff8182b720)
Location: io_uring/register.c:71
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff8182b720-ffffffff8182b79d: io_eventfd_unregister (STB_GLOBAL)
```
</details>
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
In fs/io_uring.c (ffff800010403d1c)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (c05d7780)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (c0000000005108e4)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffe0002b11c4)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8133e00d)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8132eccd)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8133badd)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
In fs/io_uring.c (ffffffff8134ec8d)
Location: fs/io_uring.c:3605
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
</details>
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
