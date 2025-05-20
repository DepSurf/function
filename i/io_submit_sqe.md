# Function: <code>io_submit_sqe</code>

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
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132fe90)
Location: fs/io_uring.c:2124
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8132fe90-ffffffff8133027b: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81343600)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81343600-ffffffff81343930: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_submit_sqe(struct io_kiocb *req, const struct io_uring_sqe *sqe, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388710)
Location: fs/io_uring.c:5859
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81388710-ffffffff8138899b: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_submit_sqe(struct io_kiocb *req, const struct io_uring_sqe *sqe, struct io_submit_link *link, struct io_comp_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813993c0)
Location: fs/io_uring.c:6670
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff813993c0-ffffffff8139960a: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a0780)
Location: fs/io_uring.c:6598
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff813a0780-ffffffff813a0971: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ef640)
Location: fs/io_uring.c:7175
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff813ef640-ffffffff813ef99f: io_submit_sqe (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff816d61d7)
Location: io_uring/io_uring.c:8502
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff81791660)
Location: io_uring/io_uring.c:2240
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff817d28f3)
Location: io_uring/io_uring.c:2265
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff81815c19)
Location: io_uring/io_uring.c:2293
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010405328)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffff800010405328-ffff800010405668: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d4f9c)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
c05d4f9c-c05d52a8: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050dd60)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
c00000000050dd60-c00000000050e19c: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af46e)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffe0002af46e-ffffffe0002af726: io_submit_sqe (STB_LOCAL)
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
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133bbe0)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8133bbe0-ffffffff8133bf10: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132c8c0)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8132c8c0-ffffffff8132cbf0: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813396b0)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff813396b0-ffffffff813399e0: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_submit_sqe(struct io_ring_ctx *ctx, struct sqe_submit *s, struct io_submit_state *state, struct io_kiocb **link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134c3e0)
Location: fs/io_uring.c:2510
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8134c3e0-ffffffff8134c70e: io_submit_sqe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_kiocb *req</code>
</li>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sqe_submit *s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_submit_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, s, state, link</code> ➡️ <code>req, sqe, link</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_comp_state *cs</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct io_kiocb **link</code> ➡️ <code>struct io_submit_link *link</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_submit_link *link</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_comp_state *cs</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, sqe, link, cs</code> ➡️ <code>ctx, req, sqe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
