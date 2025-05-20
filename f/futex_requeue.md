# Function: <code>futex_requeue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81101c80)
Location: kernel/futex.c:1603
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81101c80-ffffffff81102664: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811091d0)
Location: kernel/futex.c:1693
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811091d0-ffffffff81109b15: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811109c0)
Location: kernel/futex.c:1702
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811109c0-ffffffff81111305: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111f70)
Location: kernel/futex.c:1792
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81111f70-ffffffff81112977: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111c9c0)
Location: kernel/futex.c:1870
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8111c9c0-ffffffff8111d3e8: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81129370)
Location: kernel/futex.c:1852
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81129370-ffffffff81129e90: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135460)
Location: kernel/futex.c:1920
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81135460-ffffffff81135f87: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:1934
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81140d50-ffffffff81141852: futex_requeue (STB_LOCAL)
ffffffff81142a2d-ffffffff81142aaa: futex_requeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114c800)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114c800-ffffffff8114d321: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115d480)
Location: kernel/futex.c:1941
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115d480-ffffffff8115dc07: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811594a0)
Location: kernel/futex.c:1919
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811594a0-ffffffff81159bca: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a610)
Location: kernel/futex.c:1922
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115a610-ffffffff8115adf9: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117f4b0)
Location: kernel/futex.c:2127
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8117f4b0-ffffffff8117fde2: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/requeue.c (ffffffff811b5960)
Location: kernel/futex/requeue.c:364
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811b5960-ffffffff811b6299: futex_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/requeue.c (ffffffff811f6a90)
Location: kernel/futex/requeue.c:364
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811f6a90-ffffffff811f73c9: futex_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/requeue.c (ffffffff8120b270)
Location: kernel/futex/requeue.c:364
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff8120b270-ffffffff8120bb6d: futex_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags1, u32 *uaddr2, unsigned int flags2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/requeue.c (ffffffff81222810)
Location: kernel/futex/requeue.c:367
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_requeue
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff81222810-ffffffff812230f4: futex_requeue (STB_GLOBAL)
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
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101baa20)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffff8000101baa20-ffff8000101bb528: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c04031d4)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c04031d4-c0403c10: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c000000000220c10)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c000000000220c10-c0000000002218c0: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013ec26)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffe00013ec26-ffffffe00013f5fe: futex_requeue (STB_LOCAL)
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
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81144e20)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81144e20-ffffffff81145941: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81138130)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81138130-ffffffff81138c51: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142cd0)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81142cd0-ffffffff811437f1: futex_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int futex_requeue(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_requeue, u32 *cmpval, int requeue_pi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811502b0)
Location: kernel/futex.c:2015
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811502b0-ffffffff81150dbc: futex_requeue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags1</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int flags2</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>uaddr1, flags, uaddr2, nr_wake, nr_requeue, cmpval, requeue_pi</code> ➡️ <code>uaddr1, flags1, uaddr2, flags2, nr_wake, nr_requeue, cmpval, requeue_pi</code>
</li>
</ul>
</details>
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
