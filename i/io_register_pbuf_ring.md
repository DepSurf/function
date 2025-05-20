# Function: <code>io_register_pbuf_ring</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_register_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:12499
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff816ce100-ffffffff816ce362: io_register_pbuf_ring (STB_LOCAL)
ffffffff81e90ce8-ffffffff81e90d1c: io_register_pbuf_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_register_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179fb90)
Location: io_uring/kbuf.c:466
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8179fb90-ffffffff8179fdf9: io_register_pbuf_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_register_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e0ca0)
Location: io_uring/kbuf.c:537
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff817e0ca0-ffffffff817e0f49: io_register_pbuf_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_register_pbuf_ring(struct io_ring_ctx *ctx, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff81825280)
Location: io_uring/kbuf.c:659
Inline: False
Direct callers:
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81825280-ffffffff81825649: io_register_pbuf_ring (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
