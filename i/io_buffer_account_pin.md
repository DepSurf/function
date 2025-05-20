# Function: <code>io_buffer_account_pin</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138af60)
Location: fs/io_uring.c:8472
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff8138af60-ffffffff8138b0a6: io_buffer_account_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391690)
Location: fs/io_uring.c:8267
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81391690-ffffffff813918a5: io_buffer_account_pin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:8979
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff813df5a0-ffffffff813df7af: io_buffer_account_pin (STB_LOCAL)
ffffffff81cc58fd-ffffffff81cc591e: io_buffer_account_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:10280
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff816cd1d0-ffffffff816cd52a: io_buffer_account_pin (STB_LOCAL)
ffffffff81e90b18-ffffffff81e90b48: io_buffer_account_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:1108
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff817a08c0-ffffffff817a0bdd: io_buffer_account_pin (STB_LOCAL)
ffffffff820779c7-ffffffff820779f7: io_buffer_account_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:998
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff817e1b20-ffffffff817e1e01: io_buffer_account_pin (STB_LOCAL)
ffffffff820f7a5f-ffffffff820f7a90: io_buffer_account_pin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_buffer_account_pin(struct io_ring_ctx *ctx, struct page **pages, int nr_pages, struct io_mapped_ubuf *imu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rsrc.c (0)
Location: io_uring/rsrc.c:843
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81825ee0-ffffffff818261aa: io_buffer_account_pin (STB_LOCAL)
ffffffff821d53fb-ffffffff821d5429: io_buffer_account_pin.cold (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
