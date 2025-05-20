# Function: <code>io_wq_hash_work</code>

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
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138b0e0)
Location: fs/io-wq.c:849
Inline: False
Direct callers:
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_queue_async_work
```
**Symbols:**

```
ffffffff8138b0e0-ffffffff8138b109: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139c340)
Location: fs/io-wq.c:916
Inline: False
Direct callers:
  - fs/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff8139c340-ffffffff8139c369: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a3490)
Location: fs/io-wq.c:802
Inline: False
Direct callers:
  - fs/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff813a3490-ffffffff813a34b9: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813f2970)
Location: fs/io-wq.c:965
Inline: False
Direct callers:
  - fs/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff813f2970-ffffffff813f2999: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff816db500)
Location: io_uring/io-wq.c:980
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff816db500-ffffffff816db533: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817a75e0)
Location: io_uring/io-wq.c:967
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff817a75e0-ffffffff817a7613: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff817e8630)
Location: io_uring/io-wq.c:957
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff817e8630-ffffffff817e8663: io_wq_hash_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_wq_hash_work(struct io_wq_work *work, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io-wq.c (ffffffff8182e3d0)
Location: io_uring/io-wq.c:978
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_prep_async_work
```
**Symbols:**

```
ffffffff8182e3d0-ffffffff8182e403: io_wq_hash_work (STB_GLOBAL)
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
