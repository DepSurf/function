# Function: <code>io_queue_sqe</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132fad0)
Location: fs/io_uring.c:2066
Inline: True
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff8132fad0-ffffffff8132fe8e: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81343570)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffffffff81343570-ffffffff813435f7: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_queue_sqe(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388570)
Location: fs/io_uring.c:5816
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81388570-ffffffff8138870a: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_queue_sqe(struct io_kiocb *req, const struct io_uring_sqe *sqe, struct io_comp_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399240)
Location: fs/io_uring.c:6625
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81399240-ffffffff813993ba: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_queue_sqe(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813a0720)
Location: fs/io_uring.c:6487
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813a0720-ffffffff813a077c: io_queue_sqe (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813efae0)
Location: fs/io_uring.c:7067
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
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
In io_uring/io_uring.c (ffffffff816d620e)
Location: io_uring/io_uring.c:8285
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
In io_uring/io_uring.c (ffffffff81791698)
Location: io_uring/io_uring.c:2024
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
In io_uring/io_uring.c (ffffffff817d2925)
Location: io_uring/io_uring.c:2049
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
In io_uring/io_uring.c (ffffffff81815c4b)
Location: io_uring/io_uring.c:2079
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
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010405260)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffff800010405260-ffff800010405324: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d4f14)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
c05d4f14-c05d4f9c: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050dc80)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
c00000000050dc80-c00000000050dd5c: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af3ec)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffffffe0002af3ec-ffffffe0002af46e: io_queue_sqe (STB_LOCAL)
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
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133bb50)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffffffff8133bb50-ffffffff8133bbd7: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132c830)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffffffff8132c830-ffffffff8132c8b7: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339620)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffffffff81339620-ffffffff813396a7: io_queue_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_queue_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134c230)
Location: fs/io_uring.c:2449
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
```
**Symbols:**

```
ffffffff8134c230-ffffffff8134c2b7: io_queue_sqe (STB_LOCAL)
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
<b>Param reordered. </b>
<code>ctx, req, s</code> ➡️ <code>req, sqe</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_comp_state *cs</code>
</li>
</ul>
</details>
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
