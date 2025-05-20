# Function: <code>__io_sqe_files_unregister</code>

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
In fs/io_uring.c (ffffffff8132df12)
Location: fs/io_uring.c:2507
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff81341172)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff8137edf5)
Location: fs/io_uring.c:6364
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff8138bf60)
Location: fs/io_uring.c:7320
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81392ce0)
Location: fs/io_uring.c:7218
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff81392ce0-ffffffff81392da7: __io_sqe_files_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dfd70)
Location: fs/io_uring.c:7919
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff813dfd70-ffffffff813dfdea: __io_sqe_files_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8ea12)
Location: io_uring/io_uring.c:9256
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff81e8ea12-ffffffff81e8eaf5: __io_sqe_files_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a1270)
Location: io_uring/rsrc.c:773
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_sqe_files_unregister
```
**Symbols:**

```
ffffffff817a1270-ffffffff817a1382: __io_sqe_files_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e2460)
Location: io_uring/rsrc.c:665
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_sqe_files_unregister
```
**Symbols:**

```
ffffffff817e2460-ffffffff817e258f: __io_sqe_files_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __io_sqe_files_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81826db0)
Location: io_uring/rsrc.c:660
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/rsrc.c:io_sqe_files_register
  - io_uring/rsrc.c:io_sqe_files_unregister
```
**Symbols:**

```
ffffffff81826db0-ffffffff81826e82: __io_sqe_files_unregister (STB_GLOBAL)
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
In fs/io_uring.c (ffff800010400ffc)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (c05d25bc)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (c000000000509900)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffe0002ac9b4)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff81339752)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff8132a482)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff81337222)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
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
In fs/io_uring.c (ffffffff8134a2e2)
Location: fs/io_uring.c:3011
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_files_unregister
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
