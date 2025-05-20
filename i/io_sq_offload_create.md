# Function: <code>io_sq_offload_create</code>

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
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393e10)
Location: fs/io_uring.c:8178
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81393e10-ffffffff8139426e: io_sq_offload_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81394200)
Location: fs/io_uring.c:7973
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81394200-ffffffff81394493: io_sq_offload_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:8686
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff813e3390-ffffffff813e364f: io_sq_offload_create (STB_LOCAL)
ffffffff81cc5a45-ffffffff81cc5a6f: io_sq_offload_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e9050e)
Location: io_uring/io_uring.c:9972
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff81e9050e-ffffffff81e907b6: io_sq_offload_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/sqpoll.c (0)
Location: io_uring/sqpoll.c:333
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff820777a8-ffffffff82077809: io_sq_offload_create.cold (STB_LOCAL)
ffffffff8179ace0-ffffffff8179afac: io_sq_offload_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/sqpoll.c (0)
Location: io_uring/sqpoll.c:335
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff820f782a-ffffffff820f788b: io_sq_offload_create.cold (STB_LOCAL)
ffffffff817dbd90-ffffffff817dc05f: io_sq_offload_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int io_sq_offload_create(struct io_ring_ctx *ctx, struct io_uring_params *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/sqpoll.c (0)
Location: io_uring/sqpoll.c:343
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
```
**Symbols:**

```
ffffffff821d521d-ffffffff821d527e: io_sq_offload_create.cold (STB_LOCAL)
ffffffff81820110-ffffffff818203e1: io_sq_offload_create (STB_GLOBAL)
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
