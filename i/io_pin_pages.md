# Function: <code>io_pin_pages</code>

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
struct page **io_pin_pages(long unsigned int ubuf, long unsigned int len, int *npages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816ca030)
Location: io_uring/io_uring.c:10312
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_register_pbuf_ring
  - io_uring/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff816ca030-ffffffff816ca258: io_pin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page **io_pin_pages(long unsigned int ubuf, long unsigned int len, int *npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2190)
Location: io_uring/rsrc.c:1140
Inline: False
Direct callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/rsrc.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff817a2190-ffffffff817a23b8: io_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page **io_pin_pages(long unsigned int ubuf, long unsigned int len, int *npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e32b0)
Location: io_uring/rsrc.c:1030
Inline: False
Direct callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/rsrc.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff817e32b0-ffffffff817e3414: io_pin_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page **io_pin_pages(long unsigned int ubuf, long unsigned int len, int *npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81827360)
Location: io_uring/rsrc.c:875
Inline: False
Direct callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/rsrc.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81827360-ffffffff818274da: io_pin_pages (STB_GLOBAL)
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
