# Function: <code>io_wq_worker_cancel</code>

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
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff81389d60)
Location: fs/io-wq.c:911
Inline: False
```
**Symbols:**

```
ffffffff81389d60-ffffffff81389de3: io_wq_worker_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139ac50)
Location: fs/io-wq.c:932
Inline: False
```
**Symbols:**

```
ffffffff8139ac50-ffffffff8139accd: io_wq_worker_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a1f60)
Location: fs/io-wq.c:810
Inline: False
```
**Symbols:**

```
ffffffff813a1f60-ffffffff813a1ff2: io_wq_worker_cancel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (0)
Location: fs/io-wq.c:973
Inline: False
```
**Symbols:**

```
ffffffff813f1300-ffffffff813f139d: io_wq_worker_cancel (STB_LOCAL)
ffffffff81cc5f7e-ffffffff81cc5f99: io_wq_worker_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1001
Inline: False
```
**Symbols:**

```
ffffffff816da100-ffffffff816da1be: io_wq_worker_cancel (STB_LOCAL)
ffffffff81e92d2b-ffffffff81e92d46: io_wq_worker_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:988
Inline: False
```
**Symbols:**

```
ffffffff817a6190-ffffffff817a624e: io_wq_worker_cancel (STB_LOCAL)
ffffffff82077af0-ffffffff82077b0b: io_wq_worker_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:978
Inline: False
```
**Symbols:**

```
ffffffff817e70f0-ffffffff817e71ae: io_wq_worker_cancel (STB_LOCAL)
ffffffff820f7bca-ffffffff820f7be5: io_wq_worker_cancel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_cancel(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:999
Inline: False
```
**Symbols:**

```
ffffffff8182ceb0-ffffffff8182cf6e: io_wq_worker_cancel (STB_LOCAL)
ffffffff821d55a2-ffffffff821d55bd: io_wq_worker_cancel.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
