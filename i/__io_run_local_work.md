# Function: <code>__io_run_local_work</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __io_run_local_work(struct io_ring_ctx *ctx, bool *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1305
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_run_local_work
```
**Symbols:**

```
ffffffff820775f8-ffffffff8207760c: __io_run_local_work.cold (STB_LOCAL)
ffffffff8178efe0-ffffffff8178f180: __io_run_local_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __io_run_local_work(struct io_ring_ctx *ctx, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1402
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_run_local_work
```
**Symbols:**

```
ffffffff817d0310-ffffffff817d0496: __io_run_local_work (STB_LOCAL)
ffffffff820f763c-ffffffff820f7657: __io_run_local_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __io_run_local_work(struct io_ring_ctx *ctx, struct io_tw_state *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:1423
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_iopoll_check
  - io_uring/io_uring.c:io_run_local_work
```
**Symbols:**

```
ffffffff81813550-ffffffff818136d3: __io_run_local_work (STB_LOCAL)
ffffffff821d4ff2-ffffffff821d500d: __io_run_local_work.cold (STB_LOCAL)
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
