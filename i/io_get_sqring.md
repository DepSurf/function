# Function: <code>io_get_sqring</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8132d570)
Location: fs/io_uring.c:2228
Inline: True
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff8132d570-ffffffff8132d5c8: io_get_sqring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133ff90)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff8133ff90-ffffffff8133fffd: io_get_sqring (STB_LOCAL)
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
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000103fff68)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffff8000103fff68-ffff800010400024: io_get_sqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d1db8)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
c05d1db8-c05d1e58: io_get_sqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509420)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
c000000000509420-c0000000005094c8: io_get_sqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ac6ae)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffe0002ac6ae-ffffffe0002ac738: io_get_sqring (STB_LOCAL)
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
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338570)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81338570-ffffffff813385dd: io_get_sqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813292a0)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff813292a0-ffffffff8132930d: io_get_sqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336040)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81336040-ffffffff813360ad: io_get_sqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool io_get_sqring(struct io_ring_ctx *ctx, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81349110)
Location: fs/io_uring.c:2633
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
**Symbols:**

```
ffffffff81349110-ffffffff8134917d: io_get_sqring (STB_LOCAL)
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
