# Function: <code>io_worker_release</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff81389ffa)
Location: fs/io-wq.c:129
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139ae5a)
Location: fs/io-wq.c:139
Inline: True
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
In fs/io-wq.c (ffffffff813a2355)
Location: fs/io-wq.c:141
Inline: True
Inline callers:
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_wqe_activate_free_worker
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_worker_release(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f0ea0)
Location: fs/io-wq.c:151
Inline: False
Direct callers:
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:create_worker_cont
  - fs/io-wq.c:io_queue_worker_create
  - fs/io-wq.c:create_worker_cb
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_wqe_activate_free_worker
  - fs/io-wq.c:io_worker_cancel_cb
```
**Symbols:**

```
ffffffff813f0ea0-ffffffff813f0ed4: io_worker_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_worker_release(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9a40)
Location: io_uring/io-wq.c:154
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_worker_cancel_cb
```
**Symbols:**

```
ffffffff816d9a40-ffffffff816d9a92: io_worker_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_worker_release(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5a50)
Location: io_uring/io-wq.c:156
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_wqe_activate_free_worker
  - io_uring/io-wq.c:io_worker_cancel_cb
```
**Symbols:**

```
ffffffff817a5a50-ffffffff817a5aa2: io_worker_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_worker_release(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e6d00)
Location: io_uring/io-wq.c:149
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - io_uring/io-wq.c:io_worker_cancel_cb
```
**Symbols:**

```
ffffffff817e6d00-ffffffff817e6d52: io_worker_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_worker_release(struct io_worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182cac0)
Location: io_uring/io-wq.c:149
Inline: False
Direct callers:
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:create_worker_cont
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_queue_worker_create
  - io_uring/io-wq.c:create_worker_cb
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - io_uring/io-wq.c:io_wq_activate_free_worker
  - io_uring/io-wq.c:io_worker_cancel_cb
```
**Symbols:**

```
ffffffff8182cac0-ffffffff8182cb12: io_worker_release (STB_LOCAL)
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
