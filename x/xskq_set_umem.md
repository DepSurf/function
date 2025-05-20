# Function: <code>xskq_set_umem</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, struct xdp_umem_props *umem_props);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff819cd330)
Location: net/xdp/xsk_queue.c:10
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff819cd330-ffffffff819cd34e: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a06660)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a06660-ffffffff81a06677: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a75fd0)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a75fd0-ffffffff81a75fe7: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81aace90)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81aace90-ffffffff81aacea7: xskq_set_umem (STB_GLOBAL)
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
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffff800010d817e8)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffff800010d817e8-ffff800010d81824: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c0e7bd68)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c0e7bd68-c0e7bd90: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c000000000ec1790)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
c000000000ec1790-c000000000ec17ac: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffe0008adc2a)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffe0008adc2a-ffffffe0008adc60: xskq_set_umem (STB_GLOBAL)
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
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a4c220)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a4c220-ffffffff81a4c237: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a08e10)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81a08e10-ffffffff81a08e27: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ab80d0)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ab80d0-ffffffff81ab80e7: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xskq_set_umem(struct xsk_queue *q, u64 size, u64 chunk_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ac44f0)
Location: net/xdp/xsk_queue.c:12
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
  - net/xdp/xsk.c:xsk_bind
```
**Symbols:**

```
ffffffff81ac44f0-ffffffff81ac4507: xskq_set_umem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 size</code>
</li>
<li>
<b>Param added. </b>
<code>u64 chunk_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_umem_props *umem_props</code>
</li>
</ul>
</details>
</li>
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
