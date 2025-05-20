# Function: <code>io_wq_worker_affinity</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139b3b0)
Location: fs/io-wq.c:1170
Inline: False
```
**Symbols:**

```
ffffffff8139b3b0-ffffffff8139b453: io_wq_worker_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a1f10)
Location: fs/io-wq.c:1091
Inline: False
```
**Symbols:**

```
ffffffff813a1f10-ffffffff813a1f36: io_wq_worker_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (ffffffff81cc5f58)
Location: fs/io-wq.c:1284
Inline: True
```
**Symbols:**

```
ffffffff813f0e40-ffffffff813f0e95: io_wq_worker_affinity (STB_LOCAL)
ffffffff81cc5f44-ffffffff81cc5f7e: io_wq_worker_affinity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1310
Inline: False
```
**Symbols:**

```
ffffffff816d96c0-ffffffff816d9727: io_wq_worker_affinity (STB_LOCAL)
ffffffff81e92d01-ffffffff81e92d16: io_wq_worker_affinity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1303
Inline: False
```
**Symbols:**

```
ffffffff817a5590-ffffffff817a55f7: io_wq_worker_affinity (STB_LOCAL)
ffffffff82077ac6-ffffffff82077adb: io_wq_worker_affinity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1260
Inline: False
```
**Symbols:**

```
ffffffff817e6570-ffffffff817e65d7: io_wq_worker_affinity (STB_LOCAL)
ffffffff820f7ba0-ffffffff820f7bb5: io_wq_worker_affinity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool io_wq_worker_affinity(struct io_worker *worker, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1279
Inline: False
```
**Symbols:**

```
ffffffff8182c330-ffffffff8182c397: io_wq_worker_affinity (STB_LOCAL)
ffffffff821d5578-ffffffff821d558d: io_wq_worker_affinity.cold (STB_LOCAL)
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
