# Function: <code>xsk_reuseq_free</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a06745)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81a06650-ffffffff81a06660: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a760b5)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81a75fc0-ffffffff81a75fd0: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81aacf75)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81aace80-ffffffff81aace90: xsk_reuseq_free (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffff800010d81928)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffff800010d817b8-ffff800010d817e4: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c0e7be74)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
c0e7bd4c-c0e7bd68: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c000000000ec1920)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
c000000000ec1750-c000000000ec1784: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffe0008add98)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffe0008adae4-ffffffe0008adb0e: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a4c305)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81a4c210-ffffffff81a4c220: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a08ef5)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81a08e00-ffffffff81a08e10: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ab81b5)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81ab80c0-ffffffff81ab80d0: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xsk_reuseq_free(struct xdp_umem_fq_reuse *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ac45d5)
Location: net/xdp/xsk_queue.c:109
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_destroy
```
**Symbols:**

```
ffffffff81ac44e0-ffffffff81ac44f0: xsk_reuseq_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
