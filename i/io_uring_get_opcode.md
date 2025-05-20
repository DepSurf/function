# Function: <code>io_uring_get_opcode</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *io_uring_get_opcode(u8 opcode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816ca594)
Location: io_uring/io_uring.c:1162
Inline: True
Inline callers:
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
```
**Symbols:**

```
ffffffff816d8ee0-ffffffff816d8f0a: io_uring_get_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *io_uring_get_opcode(u8 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/opdef.c (ffffffff817a4fb0)
Location: io_uring/opdef.c:537
Inline: False
Direct callers:
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_submit_sqe
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_sqe
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff817a4fb0-ffffffff817a5008: io_uring_get_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *io_uring_get_opcode(u8 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/opdef.c (ffffffff817e5f80)
Location: io_uring/opdef.c:653
Inline: False
Direct callers:
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff817e5f80-ffffffff817e5fd1: io_uring_get_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *io_uring_get_opcode(u8 opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/opdef.c (ffffffff8182a1a0)
Location: io_uring/opdef.c:717
Inline: False
Direct callers:
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_req_failed
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_task_add
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_poll_arm
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_submit_req
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_fail_link
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_defer
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:perf_trace_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_req_failed
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_task_add
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_poll_arm
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_submit_req
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_fail_link
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_defer
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/io_uring.c:trace_event_raw_event_io_uring_queue_async_work
  - io_uring/fdinfo.c:io_uring_show_fdinfo
```
**Symbols:**

```
ffffffff8182a1a0-ffffffff8182a1f1: io_uring_get_opcode (STB_GLOBAL)
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
