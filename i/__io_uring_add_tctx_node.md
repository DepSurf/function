# Function: <code>__io_uring_add_tctx_node</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:9694
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:__do_sys_io_uring_enter
```
**Symbols:**

```
ffffffff813e05e0-ffffffff813e077c: __io_uring_add_tctx_node (STB_LOCAL)
ffffffff81cc5989-ffffffff81cc599e: __io_uring_add_tctx_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:11084
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_ringfd_register
```
**Symbols:**

```
ffffffff816c9170-ffffffff816c92b0: __io_uring_add_tctx_node (STB_LOCAL)
ffffffff81e8f3c2-ffffffff81e8f42c: __io_uring_add_tctx_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/tctx.c (0)
Location: io_uring/tctx.c:94
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/tctx.c:__io_uring_add_tctx_node_from_submit
```
**Symbols:**

```
ffffffff82077827-ffffffff8207783c: __io_uring_add_tctx_node.cold (STB_LOCAL)
ffffffff8179bc70-ffffffff8179be0f: __io_uring_add_tctx_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/tctx.c (0)
Location: io_uring/tctx.c:94
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/tctx.c:__io_uring_add_tctx_node_from_submit
```
**Symbols:**

```
ffffffff820f78a7-ffffffff820f78bc: __io_uring_add_tctx_node.cold (STB_LOCAL)
ffffffff817dcda0-ffffffff817dcf3f: __io_uring_add_tctx_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __io_uring_add_tctx_node(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/tctx.c (0)
Location: io_uring/tctx.c:94
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - io_uring/tctx.c:io_ringfd_register
  - io_uring/tctx.c:__io_uring_add_tctx_node_from_submit
```
**Symbols:**

```
ffffffff821d529a-ffffffff821d52af: __io_uring_add_tctx_node.cold (STB_LOCAL)
ffffffff818210c0-ffffffff8182128e: __io_uring_add_tctx_node (STB_GLOBAL)
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
