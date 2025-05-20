# Function: <code>ctx_flush_and_put</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139907f)
Location: fs/io_uring.c:1898
Inline: True
Inline callers:
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:tctx_task_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ctx_flush_and_put(struct io_ring_ctx *ctx, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2160
Inline: False
Direct callers:
  - fs/io_uring.c:tctx_task_work
  - fs/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff813e8180-ffffffff813e820a: ctx_flush_and_put (STB_LOCAL)
ffffffff81cc5b7a-ffffffff81cc5b8f: ctx_flush_and_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ctx_flush_and_put(struct io_ring_ctx *ctx, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2645
Inline: False
Direct callers:
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:handle_prev_tw_list
```
**Symbols:**

```
ffffffff816d5bc0-ffffffff816d5c76: ctx_flush_and_put (STB_LOCAL)
ffffffff81e91a8c-ffffffff81e91aa1: ctx_flush_and_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ctx_flush_and_put(struct io_ring_ctx *ctx, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1113
Inline: False
Direct callers:
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:handle_tw_list
  - io_uring/io_uring.c:handle_tw_list
```
**Symbols:**

```
ffffffff8178fac0-ffffffff8178fb84: ctx_flush_and_put (STB_LOCAL)
ffffffff82077641-ffffffff82077656: ctx_flush_and_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ctx_flush_and_put(struct io_ring_ctx *ctx, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1159
Inline: False
Direct callers:
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff817d1570-ffffffff817d1638: ctx_flush_and_put (STB_LOCAL)
ffffffff820f76a0-ffffffff820f76b5: ctx_flush_and_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ctx_flush_and_put(struct io_ring_ctx *ctx, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1163
Inline: False
Direct callers:
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:tctx_task_work
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff81814890-ffffffff81814955: ctx_flush_and_put (STB_LOCAL)
ffffffff821d5056-ffffffff821d506b: ctx_flush_and_put.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_tw_state *ts</code>
</li>
<li>
<b>Param removed. </b>
<code>bool *locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
