# Function: <code>io_do_iopoll</code>

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
In fs/io_uring.c (ffffffff8132e7a6)
Location: fs/io_uring.c:728
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
In fs/io_uring.c (ffffffff81341cb6)
Location: fs/io_uring.c:799
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
int io_do_iopoll(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81384d70)
Location: fs/io_uring.c:1840
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_getevents
```
**Symbols:**

```
ffffffff81384d70-ffffffff81384e98: io_do_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81396340)
Location: fs/io_uring.c:2488
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sq_thread
  - fs/io_uring.c:io_iopoll_check
```
**Symbols:**

```
ffffffff81396340-ffffffff813964d5: io_do_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min, bool resubmit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813997b0)
Location: fs/io_uring.c:2308
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813997b0-ffffffff8139994a: io_do_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, unsigned int *nr_events, long int min);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2508
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813e88b0-ffffffff813e8a08: io_do_iopoll (STB_LOCAL)
ffffffff81cc5bca-ffffffff81cc5be6: io_do_iopoll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, bool force_nonspin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3007
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_iopoll_try_reap_events
```
**Symbols:**

```
ffffffff816d6570-ffffffff816d67e0: io_do_iopoll (STB_LOCAL)
ffffffff81e91dae-ffffffff81e91dc3: io_do_iopoll.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, bool force_nonspin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:999
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff82077a2e-ffffffff82077a42: io_do_iopoll.cold (STB_LOCAL)
ffffffff817a4c70-ffffffff817a4f37: io_do_iopoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, bool force_nonspin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:1001
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff820f7b01-ffffffff820f7b1c: io_do_iopoll.cold (STB_LOCAL)
ffffffff817e5c40-ffffffff817e5f0d: io_do_iopoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_do_iopoll(struct io_ring_ctx *ctx, bool force_nonspin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:1121
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff821d54a0-ffffffff821d54b5: io_do_iopoll.cold (STB_LOCAL)
ffffffff81829f30-ffffffff8182a128: io_do_iopoll (STB_GLOBAL)
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
In fs/io_uring.c (ffff8000104027b0)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (c05d581c)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (c00000000050be98)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (ffffffe0002ae248)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (ffffffff8133a296)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (ffffffff8132afa6)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (ffffffff81337d66)
Location: fs/io_uring.c:799
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
In fs/io_uring.c (ffffffff8134cc07)
Location: fs/io_uring.c:799
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_nonspin</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *nr_events</code>
</li>
<li>
<b>Param removed. </b>
<code>long int min</code>
</li>
</ul>
</details>
</li>
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
