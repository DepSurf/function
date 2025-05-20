# Function: <code>dma_resv_wait_timeout_rcu</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81768290)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffffffff81768290-ffffffff81768565: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff818291a0)
Location: drivers/dma-buf/dma-resv.c:532
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
```
**Symbols:**

```
ffffffff818291a0-ffffffff81829574: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81839c30)
Location: drivers/dma-buf/dma-resv.c:532
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
```
**Symbols:**

```
ffffffff81839c30-ffffffff81839fab: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8181ce80)
Location: drivers/dma-buf/dma-resv.c:532
Inline: False
Direct callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_begin_cpu_access
```
**Symbols:**

```
ffffffff8181ce80-ffffffff8181d1ed: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffff800010969598)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffff800010969598-ffff8000109697e4: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c0a3f6c0)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
c0a3f6c0-c0a3f968: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (c000000000a21960)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
c000000000a21960-c000000000a21d3c: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffe0005d517c)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffffffe0005d517c-ffffffe0005d53da: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8171c980)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffffffff8171c980-ffffffff8171cc55: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff816f5de0)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffffffff816f5de0-ffffffff816f60b5: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff8175b750)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffffffff8175b750-ffffffff8175ba25: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int dma_resv_wait_timeout_rcu(struct dma_resv *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/dma-resv.c (ffffffff81776a10)
Location: drivers/dma-buf/dma-resv.c:499
Inline: False
```
**Symbols:**

```
ffffffff81776a10-ffffffff81776cfe: dma_resv_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
