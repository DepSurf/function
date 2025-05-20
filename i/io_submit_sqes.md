# Function: <code>io_submit_sqes</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, struct sqe_submit *sqes, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813308d0)
Location: fs/io_uring.c:2260
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813308d0-ffffffff81330a69: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813441b0)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813441b0-ffffffff81344426: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, struct file *ring_file, int ring_fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813889a0)
Location: fs/io_uring.c:6059
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813889a0-ffffffff81388f21: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399610)
Location: fs/io_uring.c:6918
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__io_sq_thread
```
**Symbols:**

```
ffffffff81399610-ffffffff81399bbf: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a0980)
Location: fs/io_uring.c:6743
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813a0980-ffffffff813a0e47: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:7327
Inline: False
Direct callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813ef9a0-ffffffff813eff79: io_submit_sqes (STB_LOCAL)
ffffffff81cc5d58-ffffffff81cc5d6c: io_submit_sqes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:8634
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff816d60e0-ffffffff816d656b: io_submit_sqes (STB_LOCAL)
ffffffff81e91c3a-ffffffff81e91dae: io_submit_sqes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2370
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff820776c4-ffffffff820776d8: io_submit_sqes.cold (STB_LOCAL)
ffffffff81791580-ffffffff81791965: io_submit_sqes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2397
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff820f7709-ffffffff820f771d: io_submit_sqes.cold (STB_LOCAL)
ffffffff817d2810-ffffffff817d2c02: io_submit_sqes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2428
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/sqpoll.c:io_sq_thread
```
**Symbols:**

```
ffffffff821d50bf-ffffffff821d50d3: io_submit_sqes.cold (STB_LOCAL)
ffffffff81815b30-ffffffff81815f09: io_submit_sqes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010405e50)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffff800010405e50-ffff80001040602c: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d5594)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
c05d5594-c05d57a4: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050ec00)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
c00000000050ec00-c00000000050ee98: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af9aa)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffe0002af9aa-ffffffe0002afb26: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133c790)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff8133c790-ffffffff8133ca06: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d460)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff8132d460-ffffffff8132d6d6: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a260)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff8133a260-ffffffff8133a4d6: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_submit_sqes(struct io_ring_ctx *ctx, unsigned int nr, bool has_user, bool mm_fault);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134c910)
Location: fs/io_uring.c:2668
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff8134c910-ffffffff8134cb86: io_submit_sqes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sqe_submit *sqes</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, sqes, nr, has_user, mm_fault</code> ➡️ <code>ctx, nr, has_user, mm_fault</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *ring_file</code>
</li>
<li>
<b>Param added. </b>
<code>int ring_fd</code>
</li>
<li>
<b>Param removed. </b>
<code>bool has_user</code>
</li>
<li>
<b>Param removed. </b>
<code>bool mm_fault</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct file *ring_file</code>
</li>
<li>
<b>Param removed. </b>
<code>int ring_fd</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
