# Function: <code>io_run_task_work_sig</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int io_run_task_work_sig();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138b460)
Location: fs/io_uring.c:7220
Inline: True
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_files_unregister
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff8138b460-ffffffff8138b4d7: io_run_task_work_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int io_run_task_work_sig();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393f40)
Location: fs/io_uring.c:7001
Inline: True
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff81393f40-ffffffff81393fe1: io_run_task_work_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int io_run_task_work_sig();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e1940)
Location: fs/io_uring.c:7583
Inline: True
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_cqring_wait
```
**Symbols:**

```
ffffffff813e1940-ffffffff813e19e0: io_run_task_work_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e90c4c)
Location: io_uring/io_uring.c:8889
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int io_run_task_work_sig(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81791980)
Location: io_uring/io_uring.c:2465
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/cancel.c:io_sync_cancel
```
**Symbols:**

```
ffffffff81791980-ffffffff817919e3: io_run_task_work_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_run_task_work_sig(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d3170)
Location: io_uring/io_uring.c:2488
Inline: False
Direct callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
**Symbols:**

```
ffffffff817d3170-ffffffff817d31d5: io_run_task_work_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_run_task_work_sig(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81816470)
Location: io_uring/io_uring.c:2519
Inline: False
Direct callers:
  - io_uring/cancel.c:io_sync_cancel
  - io_uring/rsrc.c:io_rsrc_ref_quiesce
```
**Symbols:**

```
ffffffff81816470-ffffffff818164ce: io_run_task_work_sig (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
