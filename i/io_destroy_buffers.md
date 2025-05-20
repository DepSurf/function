# Function: <code>io_destroy_buffers</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138511c)
Location: fs/io_uring.c:7450
Inline: True
Inline callers:
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
In fs/io_uring.c (ffffffff8138fad9)
Location: fs/io_uring.c:8681
Inline: True
Inline callers:
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
In fs/io_uring.c (ffffffff8139ac5d)
Location: fs/io_uring.c:8579
Inline: True
Inline callers:
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
In fs/io_uring.c (ffffffff813e5236)
Location: fs/io_uring.c:9286
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
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
In io_uring/io_uring.c (ffffffff81e9117b)
Location: io_uring/io_uring.c:10637
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_destroy_buffers(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179f420)
Location: io_uring/kbuf.c:246
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff8179f420-ffffffff8179f6c7: io_destroy_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_destroy_buffers(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e0690)
Location: io_uring/kbuf.c:259
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817e0690-ffffffff817e07d5: io_destroy_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_destroy_buffers(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff81824b20)
Location: io_uring/kbuf.c:306
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81824b20-ffffffff81824cc2: io_destroy_buffers (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
