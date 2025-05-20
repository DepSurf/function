# Function: <code>xskq_destroy</code>

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
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff819cd3e0)
Location: net/xdp/xsk_queue.c:56
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff819cd3e0-ffffffff819cd407: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a06710)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a06710-ffffffff81a06737: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a76080)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a76080-ffffffff81a760a9: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81aacf40)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81aacf40-ffffffff81aacf69: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ba8df0)
Location: net/xdp/xsk_queue.c:50
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ba8df0-ffffffff81ba8e1b: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81bb8650)
Location: net/xdp/xsk_queue.c:50
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81bb8650-ffffffff81bb867b: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ba7810)
Location: net/xdp/xsk_queue.c:50
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81ba7810-ffffffff81ba783b: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81c75490)
Location: net/xdp/xsk_queue.c:50
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81c75490-ffffffff81c754bb: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81e19660)
Location: net/xdp/xsk_queue.c:50
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81e19660-ffffffff81e19696: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ff0970)
Location: net/xdp/xsk_queue.c:50
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff81ff0970-ffffffff81ff09a6: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff8206cb20)
Location: net/xdp/xsk_queue.c:49
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff8206cb20-ffffffff8206cb56: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff821409c0)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
  - net/xdp/xsk_buff_pool.c:xp_release_deferred
```
**Symbols:**

```
ffffffff821409c0-ffffffff821409f6: xskq_destroy (STB_GLOBAL)
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
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffff800010d818d8)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffff800010d818d8-ffff800010d81910: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c0e7be30)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c0e7be30-c0e7be60: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (c000000000ec18a0)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c000000000ec18a0-c000000000ec18f4: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffe0008add4c)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffe0008add4c-ffffffe0008add82: xskq_destroy (STB_GLOBAL)
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
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a4c2d0)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a4c2d0-ffffffff81a4c2f9: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81a08ec0)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a08ec0-ffffffff81a08ee9: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ab8180)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ab8180-ffffffff81ab81a9: xskq_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xskq_destroy(struct xsk_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk_queue.c (ffffffff81ac45a0)
Location: net/xdp/xsk_queue.c:59
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xsk.c:xsk_release
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ac45a0-ffffffff81ac45c9: xskq_destroy (STB_GLOBAL)
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
