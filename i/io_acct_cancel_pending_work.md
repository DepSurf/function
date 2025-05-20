# Function: <code>io_acct_cancel_pending_work</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff813f13a0)
Location: fs/io-wq.c:1011
Inline: True
Direct callers:
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_cancel_pending_work
  - fs/io-wq.c:io_wqe_enqueue
  - fs/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff813f13a0-ffffffff813f159b: io_acct_cancel_pending_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_acct_cancel_pending_work(struct io_wqe *wqe, struct io_wqe_acct *acct, struct io_cb_cancel_data *match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9e20)
Location: io_uring/io-wq.c:1037
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wqe_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff816d9e20-ffffffff816da07b: io_acct_cancel_pending_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_acct_cancel_pending_work(struct io_wqe *wqe, struct io_wqe_acct *acct, struct io_cb_cancel_data *match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5e90)
Location: io_uring/io-wq.c:1024
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wqe_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_cancel_pending_work
  - io_uring/io-wq.c:io_wqe_enqueue
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff817a5e90-ffffffff817a60eb: io_acct_cancel_pending_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_acct_cancel_pending_work(struct io_wq *wq, struct io_wq_acct *acct, struct io_cb_cancel_data *match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e6a10)
Location: io_uring/io-wq.c:1014
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_cancel_pending_work
  - io_uring/io-wq.c:io_wq_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff817e6a10-ffffffff817e6c58: io_acct_cancel_pending_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_acct_cancel_pending_work(struct io_wq *wq, struct io_wq_acct *acct, struct io_cb_cancel_data *match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182c7d0)
Location: io_uring/io-wq.c:1035
Inline: False
Direct callers:
  - io_uring/io-wq.c:io_wq_cancel_pending_work
  - io_uring/io-wq.c:io_wq_cancel_pending_work
  - io_uring/io-wq.c:io_wq_enqueue
  - io_uring/io-wq.c:create_worker_cont
```
**Symbols:**

```
ffffffff8182c7d0-ffffffff8182ca18: io_acct_cancel_pending_work (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_wq *wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wqe *wqe</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct io_wqe_acct *acct</code> ➡️ <code>struct io_wq_acct *acct</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
