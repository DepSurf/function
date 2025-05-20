# Function: <code>io_get_next_work</code>

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
struct io_wq_work *io_get_next_work(struct io_wqe *wqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff81389c50)
Location: fs/io-wq.c:386
Inline: False
Direct callers:
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff81389c50-ffffffff81389cfb: io_get_next_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct io_wq_work *io_get_next_work(struct io_wqe *wqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139ab80)
Location: fs/io-wq.c:401
Inline: False
Direct callers:
  - fs/io-wq.c:io_worker_handle_work
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8139ab80-ffffffff8139ac2b: io_get_next_work (STB_LOCAL)
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
In fs/io-wq.c (ffffffff813a2bca)
Location: fs/io-wq.c:420
Inline: True
Inline callers:
  - fs/io-wq.c:io_worker_handle_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff813f1a50)
Location: fs/io-wq.c:457
Inline: True
Direct callers:
  - fs/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff813f1a50-ffffffff813f1d11: io_get_next_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9730)
Location: io_uring/io-wq.c:464
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff816d9730-ffffffff816d99f4: io_get_next_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5610)
Location: io_uring/io-wq.c:466
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff817a5610-ffffffff817a58d4: io_get_next_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e65f0)
Location: io_uring/io-wq.c:463
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff817e65f0-ffffffff817e6893: io_get_next_work.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182c3b0)
Location: io_uring/io-wq.c:475
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8182c3b0-ffffffff8182c653: io_get_next_work.isra.0 (STB_LOCAL)
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
</ul>
