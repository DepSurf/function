# Function: <code>__bpf_trace_io_uring_link</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_trace_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137adf0)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff8137adf0-ffffffff8137adfb: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389120)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff81389120-ffffffff8138912b: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390220)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff81390220-ffffffff8139022b: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dd940)
Location: include/trace/events/io_uring.h:208
Inline: False
```
**Symbols:**

```
ffffffff813dd940-ffffffff813dd94b: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_io_uring_link(void *__data, void *ctx, void *req, void *target_req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7120)
Location: include/trace/events/io_uring.h:234
Inline: False
```
**Symbols:**

```
ffffffff816c7120-ffffffff816c7137: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_link(void *__data, struct io_kiocb *req, struct io_kiocb *target_req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817884a0)
Location: include/trace/events/io_uring.h:223
Inline: True
```
**Symbols:**

```
ffffffff817884a0-ffffffff817884b5: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_link(void *__data, struct io_kiocb *req, struct io_kiocb *target_req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c8bb0)
Location: include/trace/events/io_uring.h:223
Inline: True
```
**Symbols:**

```
ffffffff817c8bb0-ffffffff817c8bc5: __bpf_trace_io_uring_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_io_uring_link(void *__data, struct io_kiocb *req, struct io_kiocb *target_req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180d880)
Location: include/trace/events/io_uring.h:223
Inline: True
```
**Symbols:**

```
ffffffff8180d880-ffffffff8180d895: __bpf_trace_io_uring_link (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, ctx, req, target_req</code> ➡️ <code>__data, req, target_req</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *req</code> ➡️ <code>struct io_kiocb *req</code>
</li>
<li>
<b>Param type changed. </b>
<code>void *target_req</code> ➡️ <code>struct io_kiocb *target_req</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
