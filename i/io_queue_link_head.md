# Function: <code>io_queue_link_head</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81343930)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81343930-ffffffff81343a26: io_queue_link_head (STB_LOCAL)
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
In fs/io_uring.c (ffffffff81388bab)
Location: fs/io_uring.c:5850
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
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
In fs/io_uring.c (ffffffff81399842)
Location: fs/io_uring.c:6655
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010405668)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffff800010405668-ffff800010405804: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d52a8)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
c05d52a8-c05d53c4: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050e1a0)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
c00000000050e1a0-c00000000050e360: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002af726)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffe0002af726-ffffffe0002af848: io_queue_link_head (STB_LOCAL)
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
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133bf10)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8133bf10-ffffffff8133c006: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132cbf0)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8132cbf0-ffffffff8132cce0: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813399e0)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff813399e0-ffffffff81339ad6: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_queue_link_head(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s, struct io_kiocb *shadow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134c2c0)
Location: fs/io_uring.c:2466
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8134c2c0-ffffffff8134c3d4: io_queue_link_head (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
