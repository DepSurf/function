# Function: <code>io_unregister_pbuf_ring</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d854e)
Location: io_uring/io_uring.c:12558
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_unregister_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179fe10)
Location: io_uring/kbuf.c:525
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8179fe10-ffffffff8179ff67: io_unregister_pbuf_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_unregister_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e0f60)
Location: io_uring/kbuf.c:601
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817e0f60-ffffffff817e1088: io_unregister_pbuf_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_unregister_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff81825660)
Location: io_uring/kbuf.c:725
Inline: False
Direct callers:
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81825660-ffffffff8182578b: io_unregister_pbuf_ring (STB_GLOBAL)
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
