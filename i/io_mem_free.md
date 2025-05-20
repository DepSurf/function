# Function: <code>io_mem_free</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d2f0)
Location: fs/io_uring.c:2804
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff8132d2f0-ffffffff8132d34d: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81340270)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81340270-ffffffff813402cd: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8137c778)
Location: fs/io_uring.c:7156
Inline: True
Inline callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
Direct callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff8137c640-ffffffff8137c698: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8138ac90)
Location: fs/io_uring.c:8324
Inline: True
Inline callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
Direct callers:
  - fs/io_uring.c:io_allocate_scq_urings
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff8138ab70-ffffffff8138abc8: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff8139a07c)
Location: fs/io_uring.c:8109
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81392170-ffffffff813921c8: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (ffffffff813e9179)
Location: fs/io_uring.c:8822
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff813dfca0-ffffffff813dfcf8: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8f50d)
Location: io_uring/io_uring.c:10112
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
Direct callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81e8f42c-ffffffff81e8f452: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a58c)
Location: io_uring/io_uring.c:2583
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
Direct callers:
  - io_uring/io_uring.c:io_allocate_scq_urings
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff8178a410-ffffffff8178a4ad: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff817caca0)
Location: io_uring/io_uring.c:2650
Inline: True
```
**Symbols:**

```
ffffffff817caca0-ffffffff817cad3d: io_mem_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81810f73)
Location: io_uring/io_uring.c:2691
Inline: True
Direct callers:
  - io_uring/kbuf.c:io_kbuf_mmap_list_free
  - io_uring/kbuf.c:io_kbuf_mmap_list_free
  - io_uring/kbuf.c:io_register_pbuf_ring
```
**Symbols:**

```
ffffffff818164e0-ffffffff8181657b: io_mem_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010401220)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffff800010401220-ffff8000104012a0: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d260c)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
c05d260c-c05d2684: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509980)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
c000000000509980-c000000000509a18: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ac9fe)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffe0002ac9fe-ffffffe0002aca6a: io_mem_free (STB_LOCAL)
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
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338850)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81338850-ffffffff813388ad: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81329580)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81329580-ffffffff813295dd: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336320)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff81336320-ffffffff8133637d: io_mem_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_mem_free(void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813493f0)
Location: fs/io_uring.c:3331
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
**Symbols:**

```
ffffffff813493f0-ffffffff8134944d: io_mem_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
