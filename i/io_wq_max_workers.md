# Function: <code>io_wq_max_workers</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_wq_max_workers(struct io_wq *wq, int *new_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f3310)
Location: fs/io-wq.c:1345
Inline: False
Direct callers:
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:io_register_iowq_max_workers
  - fs/io_uring.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff813f3310-ffffffff813f3477: io_wq_max_workers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_wq_max_workers(struct io_wq *wq, int *new_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816dbeb0)
Location: io_uring/io-wq.c:1371
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff816dbeb0-ffffffff816dc01d: io_wq_max_workers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_wq_max_workers(struct io_wq *wq, int *new_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a7fc0)
Location: io_uring/io-wq.c:1364
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff817a7fc0-ffffffff817a811c: io_wq_max_workers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_wq_max_workers(struct io_wq *wq, int *new_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e8e80)
Location: io_uring/io-wq.c:1317
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/io_uring.c:io_register_iowq_max_workers
  - io_uring/tctx.c:__io_uring_add_tctx_node
```
**Symbols:**

```
ffffffff817e8e80-ffffffff817e8f67: io_wq_max_workers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_wq_max_workers(struct io_wq *wq, int *new_count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182ec30)
Location: io_uring/io-wq.c:1336
Inline: False
Direct callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/register.c:io_register_iowq_max_workers
  - io_uring/register.c:io_register_iowq_max_workers
```
**Symbols:**

```
ffffffff8182ec30-ffffffff8182ed17: io_wq_max_workers (STB_GLOBAL)
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
