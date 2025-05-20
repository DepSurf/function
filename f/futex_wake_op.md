# Function: <code>futex_wake_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81100f70)
Location: kernel/futex.c:1366
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81100f70-ffffffff81101586: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81107f30)
Location: kernel/futex.c:1456
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81107f30-ffffffff8110854c: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110f720)
Location: kernel/futex.c:1465
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8110f720-ffffffff8110fd3c: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81110b20)
Location: kernel/futex.c:1555
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81110b20-ffffffff81111064: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111d3f0)
Location: kernel/futex.c:1633
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8111d3f0-ffffffff8111d9c7: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112b1d1)
Location: kernel/futex.c:1615
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81134dd0)
Location: kernel/futex.c:1683
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81134dd0-ffffffff81135460: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811401b0)
Location: kernel/futex.c:1697
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811401b0-ffffffff81140788: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114c220)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114c220-ffffffff8114c7f8: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115dc10)
Location: kernel/futex.c:1700
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115dc10-ffffffff8115dffe: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159bd0)
Location: kernel/futex.c:1685
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81159bd0-ffffffff81159f30: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a210)
Location: kernel/futex.c:1688
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115a210-ffffffff8115a570: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117ec20)
Location: kernel/futex.c:1747
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8117ec20-ffffffff8117ef7a: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b6e50)
Location: kernel/futex/waitwake.c:238
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811b6e50-ffffffff811b71bd: futex_wake_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f7fe0)
Location: kernel/futex/waitwake.c:238
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811f7fe0-ffffffff811f834d: futex_wake_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120c780)
Location: kernel/futex/waitwake.c:238
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff8120c780-ffffffff8120cb07: futex_wake_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff81223b50)
Location: kernel/futex/waitwake.c:253
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff81223b50-ffffffff81223ed9: futex_wake_op (STB_GLOBAL)
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
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bbab8)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffff8000101bbab8-ffff8000101bbf2c: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0404520)
Location: kernel/futex.c:1772
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c000000000220710)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c000000000220710-c000000000220c08: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013e650)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffe00013e650-ffffffe00013ec26: futex_wake_op (STB_LOCAL)
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
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81144840)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81144840-ffffffff81144e18: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81137b50)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81137b50-ffffffff81138128: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811426f0)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811426f0-ffffffff81142cc8: futex_wake_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int futex_wake_op(u32 *uaddr1, unsigned int flags, u32 *uaddr2, int nr_wake, int nr_wake2, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114eb30)
Location: kernel/futex.c:1772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114eb30-ffffffff8114f146: futex_wake_op (STB_LOCAL)
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
