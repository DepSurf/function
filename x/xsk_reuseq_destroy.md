# Function: <code>xsk_reuseq_destroy</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a06740)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a06740-ffffffff81a06767: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a760b0)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a760b0-ffffffff81a760d7: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81aacf70)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81aacf70-ffffffff81aacf97: xsk_reuseq_destroy (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffff800010d81910)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffff800010d81910-ffff800010d81940: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c0e7be60)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c0e7be60-c0e7be8c: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c000000000ec1900)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c000000000ec1900-c000000000ec194c: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffe0008add82)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffe0008add82-ffffffe0008addb0: xsk_reuseq_destroy (STB_GLOBAL)
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
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a4c300)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a4c300-ffffffff81a4c327: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a08ef0)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a08ef0-ffffffff81a08f17: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ab81b0)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ab81b0-ffffffff81ab81d7: xsk_reuseq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xsk_reuseq_destroy(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ac45d0)
Location: net/xdp/xsk_queue.c:115
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ac45d0-ffffffff81ac45f7: xsk_reuseq_destroy (STB_GLOBAL)
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
