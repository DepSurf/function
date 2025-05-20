# Function: <code>futex_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81100310)
Location: kernel/futex.c:2269
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_restart
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81100310-ffffffff81100584: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81107c50)
Location: kernel/futex.c:2393
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff81107c50-ffffffff81107ebf: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110f440)
Location: kernel/futex.c:2402
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8110f440-ffffffff8110f6aa: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811105f0)
Location: kernel/futex.c:2488
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff811105f0-ffffffff8111083d: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111bd90)
Location: kernel/futex.c:2629
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8111bd90-ffffffff8111bfdd: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811290b0)
Location: kernel/futex.c:2611
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff811290b0-ffffffff811292f8: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811345a0)
Location: kernel/futex.c:2679
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff811345a0-ffffffff811347e8: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113f560)
Location: kernel/futex.c:2710
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8113f560-ffffffff8113f7c6: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114b020)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8114b020-ffffffff8114b276: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115bb90)
Location: kernel/futex.c:2715
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8115bb90-ffffffff8115bdc7: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157770)
Location: kernel/futex.c:2683
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff81157770-ffffffff811579c9: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158bc0)
Location: kernel/futex.c:2682
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff81158bc0-ffffffff81158e0d: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117da90)
Location: kernel/futex.c:2929
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8117da90-ffffffff8117dcdd: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b7590)
Location: kernel/futex/waitwake.c:632
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/waitwake.c:futex_wait_restart
```
**Symbols:**

```
ffffffff811b7590-ffffffff811b77fb: futex_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f8720)
Location: kernel/futex/waitwake.c:632
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/waitwake.c:futex_wait_restart
```
**Symbols:**

```
ffffffff811f8720-ffffffff811f898b: futex_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120cee0)
Location: kernel/futex/waitwake.c:632
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/waitwake.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8120cee0-ffffffff8120d150: futex_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff812247c0)
Location: kernel/futex/waitwake.c:688
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/waitwake.c:futex_wait_restart
```
**Symbols:**

```
ffffffff812247c0-ffffffff812248d8: futex_wait (STB_GLOBAL)
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
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b92f0)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffff8000101b92f0-ffff8000101b9530: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c04024e4)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
c04024e4-c0402744: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021e870)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
c00000000021e870-c00000000021eb70: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013d05c)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffe00013d05c-ffffffe00013d28a: futex_wait (STB_LOCAL)
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
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81143640)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff81143640-ffffffff81143896: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81137500)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff81137500-ffffffff81137756: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811414f0)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff811414f0-ffffffff81141746: futex_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int futex_wait(u32 *uaddr, unsigned int flags, u32 val, ktime_t *abs_time, u32 bitset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114e860)
Location: kernel/futex.c:2802
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_wait_restart
```
**Symbols:**

```
ffffffff8114e860-ffffffff8114eab2: futex_wait (STB_LOCAL)
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
