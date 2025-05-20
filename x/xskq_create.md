# Function: <code>xskq_create</code>

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
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff819cd350)
Location: net/xdp/xsk_queue.c:28
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff819cd350-ffffffff819cd3df: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a06680)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81a06680-ffffffff81a0670f: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a75ff0)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81a75ff0-ffffffff81a7607f: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81aaceb0)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81aaceb0-ffffffff81aacf3f: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ba8d60)
Location: net/xdp/xsk_queue.c:23
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81ba8d60-ffffffff81ba8de7: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81bb85b0)
Location: net/xdp/xsk_queue.c:23
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81bb85b0-ffffffff81bb8645: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ba7770)
Location: net/xdp/xsk_queue.c:23
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81ba7770-ffffffff81ba7805: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81c753f0)
Location: net/xdp/xsk_queue.c:23
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81c753f0-ffffffff81c75485: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81e195c0)
Location: net/xdp/xsk_queue.c:23
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81e195c0-ffffffff81e1965f: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ff08c0)
Location: net/xdp/xsk_queue.c:23
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81ff08c0-ffffffff81ff095f: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff8206ca70)
Location: net/xdp/xsk_queue.c:24
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff8206ca70-ffffffff8206cb10: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff821408e0)
Location: net/xdp/xsk_queue.c:24
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff821408e0-ffffffff821409ad: xskq_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffff800010d81828)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffff800010d81828-ffff800010d818d8: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c0e7bd90)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
c0e7bd90-c0e7be30: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c000000000ec17b0)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
c000000000ec17b0-c000000000ec1894: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffe0008adc60)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffe0008adc60-ffffffe0008add4c: xskq_create (STB_GLOBAL)
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
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a4c240)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81a4c240-ffffffff81a4c2cf: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a08e30)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81a08e30-ffffffff81a08ebf: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ab80f0)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81ab80f0-ffffffff81ab817f: xskq_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xsk_queue *xskq_create(u32 nentries, bool umem_queue);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ac4510)
Location: net/xdp/xsk_queue.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_init_queue
```
**Symbols:**

```
ffffffff81ac4510-ffffffff81ac459f: xskq_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
