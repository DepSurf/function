# Function: <code>io_req_rw_complete</code>

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
void io_req_rw_complete(struct io_kiocb *req, bool *locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:286
Inline: False
```
**Symbols:**

```
ffffffff817a3db0-ffffffff817a3e1b: io_req_rw_complete (STB_LOCAL)
ffffffff82077a0c-ffffffff82077a2e: io_req_rw_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void io_req_rw_complete(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:286
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff820f7adf-ffffffff820f7b01: io_req_rw_complete.cold (STB_LOCAL)
ffffffff817e4e10-ffffffff817e4e7b: io_req_rw_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_req_rw_complete(struct io_kiocb *req, struct io_tw_state *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:300
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_run_local_work
  - io_uring/io_uring.c:tctx_task_work
```
**Symbols:**

```
ffffffff821d547e-ffffffff821d54a0: io_req_rw_complete.cold (STB_LOCAL)
ffffffff81829350-ffffffff8182940b: io_req_rw_complete (STB_GLOBAL)
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
