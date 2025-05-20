# Function: <code>io_wq_worker_wake</code>

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
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff81389d20)
Location: fs/io-wq.c:1120
Inline: False
```
**Symbols:**

```
ffffffff81389d20-ffffffff81389d36: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139ac30)
Location: fs/io-wq.c:751
Inline: False
```
**Symbols:**

```
ffffffff8139ac30-ffffffff8139ac46: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a2040)
Location: fs/io-wq.c:721
Inline: False
```
**Symbols:**

```
ffffffff813a2040-ffffffff813a2095: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f0de0)
Location: fs/io-wq.c:860
Inline: False
```
**Symbols:**

```
ffffffff813f0de0-ffffffff813f0e35: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816d9a00)
Location: io_uring/io-wq.c:872
Inline: False
```
**Symbols:**

```
ffffffff816d9a00-ffffffff816d9a3e: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a5a00)
Location: io_uring/io-wq.c:859
Inline: False
```
**Symbols:**

```
ffffffff817a5a00-ffffffff817a5a3e: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e69c0)
Location: io_uring/io-wq.c:858
Inline: False
```
**Symbols:**

```
ffffffff817e69c0-ffffffff817e69fe: io_wq_worker_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_wq_worker_wake(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182c780)
Location: io_uring/io-wq.c:882
Inline: False
```
**Symbols:**

```
ffffffff8182c780-ffffffff8182c7be: io_wq_worker_wake (STB_LOCAL)
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
