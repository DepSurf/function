# Function: <code>io_req_caches_free</code>

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
In fs/io_uring.c (ffffffff8139ade9)
Location: fs/io_uring.c:8600
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
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
In fs/io_uring.c (ffffffff813e53fa)
Location: fs/io_uring.c:9305
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_req_caches_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e7d9)
Location: io_uring/io_uring.c:10664
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81e8e7d9-ffffffff81e8e85c: io_req_caches_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_req_caches_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178b790)
Location: io_uring/io_uring.c:2690
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff8178b790-ffffffff8178b8af: io_req_caches_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_req_caches_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cc030)
Location: io_uring/io_uring.c:2842
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817cc030-ffffffff817cc151: io_req_caches_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_req_caches_free(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81810e10)
Location: io_uring/io_uring.c:2853
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff81810e10-ffffffff81810f31: io_req_caches_free (STB_LOCAL)
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
