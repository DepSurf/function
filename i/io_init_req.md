# Function: <code>io_init_req</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137e7c0)
Location: fs/io_uring.c:6002
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8137e7c0-ffffffff8137e993: io_init_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe, struct io_submit_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395520)
Location: fs/io_uring.c:6838
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81395520-ffffffff813957ce: io_init_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393400)
Location: fs/io_uring.c:6533
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff81393400-ffffffff813935c2: io_init_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:7113
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
```
**Symbols:**

```
ffffffff813e13f0-ffffffff813e16b2: io_init_req (STB_LOCAL)
ffffffff81cc5a2a-ffffffff81cc5a45: io_init_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:8371
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff816cfb10-ffffffff816cfdd0: io_init_req (STB_LOCAL)
ffffffff81e913c0-ffffffff81e913db: io_init_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2109
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8178bea0-ffffffff8178c17e: io_init_req (STB_LOCAL)
ffffffff82077543-ffffffff8207755e: io_init_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2134
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff817cd000-ffffffff817cd2bb: io_init_req (STB_LOCAL)
ffffffff820f7582-ffffffff820f759d: io_init_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_init_req(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2162
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8180e5a0-ffffffff8180e85f: io_init_req (STB_LOCAL)
ffffffff821d4f7a-ffffffff821d4f95: io_init_req.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_submit_state *state</code>
</li>
</ul>
</details>
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
