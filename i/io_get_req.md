# Function: <code>io_get_req</code>

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
In fs/io_uring.c (ffffffff8132fec9)
Location: fs/io_uring.c:550
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813412a0)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813412a0-ffffffff813413f5: io_get_req (STB_LOCAL)
```
</details>
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
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010401de8)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffff800010401de8-ffff800010401fac: io_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d3238)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
c05d3238-c05d33f8: io_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050aca0)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
c00000000050aca0-c00000000050aee0: io_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ad5fa)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffe0002ad5fa-ffffffe0002ad776: io_get_req (STB_LOCAL)
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
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339880)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81339880-ffffffff813399d5: io_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132a5b0)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff8132a5b0-ffffffff8132a705: io_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81337350)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81337350-ffffffff813374a5: io_get_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct io_kiocb *io_get_req(struct io_ring_ctx *ctx, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134a5d0)
Location: fs/io_uring.c:612
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff8134a5d0-ffffffff8134a76c: io_get_req (STB_LOCAL)
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
