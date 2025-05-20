# Function: <code>io_wqe_dec_running</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff8138a350)
Location: fs/io-wq.c:304
Inline: True
Direct callers:
  - fs/io-wq.c:io_wq_worker_sleeping
  - fs/io-wq.c:__io_worker_busy
```
**Symbols:**

```
ffffffff8138a350-ffffffff8138a389: io_wqe_dec_running.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff8139b2a0)
Location: fs/io-wq.c:318
Inline: True
Direct callers:
  - fs/io-wq.c:io_wq_worker_sleeping
  - fs/io-wq.c:__io_worker_busy
```
**Symbols:**

```
ffffffff8139b2a0-ffffffff8139b2d9: io_wqe_dec_running.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff813a2640)
Location: fs/io-wq.c:335
Inline: True
Direct callers:
  - fs/io-wq.c:io_wq_worker_sleeping
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff813a2640-ffffffff813a2729: io_wqe_dec_running.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_wqe_dec_running(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f1d20)
Location: fs/io-wq.c:386
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_worker_sleeping
  - fs/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff813f1d20-ffffffff813f1db5: io_wqe_dec_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_wqe_dec_running(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816da3b0)
Location: io_uring/io-wq.c:393
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_worker_sleeping
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff816da3b0-ffffffff816da4b2: io_wqe_dec_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_wqe_dec_running(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a6490)
Location: io_uring/io-wq.c:395
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_worker_sleeping
  - io_uring/io-wq.c:io_wqe_worker
```
**Symbols:**

```
ffffffff817a6490-ffffffff817a657b: io_wqe_dec_running (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
