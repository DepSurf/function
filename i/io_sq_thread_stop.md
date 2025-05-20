# Function: <code>io_sq_thread_stop</code>

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
In fs/io_uring.c (ffffffff81331445)
Location: fs/io_uring.c:2537
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_finish_async
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (ffffffff813401e5)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81385066)
Location: fs/io_uring.c:6430
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_sq_thread_stop(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138cb20)
Location: fs/io_uring.c:7491
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sq_offload_create
```
**Symbols:**

```
ffffffff8138cb20-ffffffff8138cc6d: io_sq_thread_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81392f85)
Location: fs/io_uring.c:7284
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dff3f)
Location: fs/io_uring.c:7985
Inline: True
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
In io_uring/io_uring.c (ffffffff81e8f747)
Location: io_uring/io_uring.c:9335
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_sq_thread_stop(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8179aa00)
Location: io_uring/sqpoll.c:54
Inline: False
```
**Symbols:**

```
ffffffff8179aa00-ffffffff8179aa71: io_sq_thread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_sq_thread_stop(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff817dbab0)
Location: io_uring/sqpoll.c:54
Inline: False
```
**Symbols:**

```
ffffffff817dbab0-ffffffff817dbb21: io_sq_thread_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_sq_thread_stop(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8181fe30)
Location: io_uring/sqpoll.c:54
Inline: False
```
**Symbols:**

```
ffffffff8181fe30-ffffffff8181fea1: io_sq_thread_stop (STB_GLOBAL)
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
In fs/io_uring.c (ffff8000104002a0)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (c05d2534)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (c000000000509840)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (ffffffe0002ac944)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (ffffffff813387c5)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (ffffffff813294f5)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (ffffffff81336295)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
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
In fs/io_uring.c (ffffffff81349365)
Location: fs/io_uring.c:3041
Inline: True
Inline callers:
  - fs/io_uring.c:io_finish_async
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
