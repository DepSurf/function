# Function: <code>create_io_worker</code>

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
bool create_io_worker(struct io_wq *wq, struct io_wqe *wqe, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138a7c0)
Location: fs/io-wq.c:641
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
```
**Symbols:**

```
ffffffff8138a7c0-ffffffff8138a91c: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool create_io_worker(struct io_wq *wq, struct io_wqe *wqe, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139b4f0)
Location: fs/io-wq.c:674
Inline: False
Direct callers:
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
```
**Symbols:**

```
ffffffff8139b4f0-ffffffff8139b694: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void create_io_worker(struct io_wq *wq, struct io_wqe *wqe, int index, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a2730)
Location: fs/io-wq.c:649
Inline: False
Direct callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:create_worker_cb
```
**Symbols:**

```
ffffffff813a2730-ffffffff813a28f7: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool create_io_worker(struct io_wq *wq, struct io_wqe *wqe, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f1610)
Location: fs/io-wq.c:794
Inline: False
Direct callers:
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:create_worker_cb
```
**Symbols:**

```
ffffffff813f1610-ffffffff813f17d4: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool create_io_worker(struct io_wq *wq, struct io_wqe *wqe, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816da6f0)
Location: io_uring/io-wq.c:806
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:create_worker_cb
```
**Symbols:**

```
ffffffff816da6f0-ffffffff816da8b8: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool create_io_worker(struct io_wq *wq, struct io_wqe *wqe, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a67e0)
Location: io_uring/io-wq.c:793
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:create_worker_cb
```
**Symbols:**

```
ffffffff817a67e0-ffffffff817a69a8: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool create_io_worker(struct io_wq *wq, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e7760)
Location: io_uring/io-wq.c:792
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:create_worker_cb
```
**Symbols:**

```
ffffffff817e7760-ffffffff817e7926: create_io_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool create_io_worker(struct io_wq *wq, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182d540)
Location: io_uring/io-wq.c:816
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:create_worker_cb
```
**Symbols:**

```
ffffffff8182d540-ffffffff8182d734: create_io_worker (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool first</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool first</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
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
<b>Param removed. </b>
<code>struct io_wqe *wqe</code>
</li>
<li>
<b>Param reordered. </b>
<code>wq, wqe, index</code> ➡️ <code>wq, index</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
