# Function: <code>__io_get_cqe</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
struct io_uring_cqe *__io_get_cqe(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c4d70)
Location: io_uring/io_uring.c:1987
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff816c4d70-ffffffff816c4e35: __io_get_cqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_uring_cqe *__io_get_cqe(struct io_ring_ctx *ctx, bool overflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178d440)
Location: io_uring/io_uring.c:783
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:__io_fill_cqe_req
  - io_uring/rw.c:__io_fill_cqe_req
```
**Symbols:**

```
ffffffff8178d440-ffffffff8178d543: __io_get_cqe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_uring_cqe *__io_get_cqe(struct io_ring_ctx *ctx, bool overflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ce820)
Location: io_uring/io_uring.c:833
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_fill_cqe_aux
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:__io_fill_cqe_req
  - io_uring/rw.c:__io_fill_cqe_req
```
**Symbols:**

```
ffffffff817ce820-ffffffff817ce925: __io_get_cqe (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool overflow</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
