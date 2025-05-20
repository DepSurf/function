# Function: <code>io_ring_ctx_alloc</code>

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
In fs/io_uring.c (ffffffff81330f17)
Location: fs/io_uring.c:394
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff81344a9f)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137cd00)
Location: fs/io_uring.c:960
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8137cd00-ffffffff8137d029: io_ring_ctx_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138b4e0)
Location: fs/io_uring.c:1284
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8138b4e0-ffffffff8138b806: io_ring_ctx_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813926f0)
Location: fs/io_uring.c:1145
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff813926f0-ffffffff81392a18: io_ring_ctx_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:1305
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff813e0980-ffffffff813e0d35: io_ring_ctx_alloc (STB_LOCAL)
ffffffff81cc599e-ffffffff81cc5a0f: io_ring_ctx_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8ecfe)
Location: io_uring/io_uring.c:1671
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81e8ecfe-ffffffff81e8f0ba: io_ring_ctx_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81789f80)
Location: io_uring/io_uring.c:275
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81789f80-ffffffff8178a36c: io_ring_ctx_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817ca890)
Location: io_uring/io_uring.c:272
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff817ca890-ffffffff817cac8d: io_ring_ctx_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_ring_ctx *io_ring_ctx_alloc(struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180e170)
Location: io_uring/io_uring.c:287
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff8180e170-ffffffff8180e58c: io_ring_ctx_alloc (STB_LOCAL)
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
In fs/io_uring.c (ffff800010402ee0)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (c05d6374)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (c00000000050f820)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffe0002b070e)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8133d07f)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8132dd3f)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8133ab4f)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
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
In fs/io_uring.c (ffffffff8134dcff)
Location: fs/io_uring.c:395
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
