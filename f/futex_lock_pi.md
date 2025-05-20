# Function: <code>futex_lock_pi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811018a0)
Location: kernel/futex.c:2369
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811018a0-ffffffff81101c77: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81108df0)
Location: kernel/futex.c:2493
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81108df0-ffffffff811091c7: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811105e0)
Location: kernel/futex.c:2502
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811105e0-ffffffff811109b7: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111ad0)
Location: kernel/futex.c:2588
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81111ad0-ffffffff81111f6a: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111d9d0)
Location: kernel/futex.c:2729
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8111d9d0-ffffffff8111de81: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112a420)
Location: kernel/futex.c:2711
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8112a420-ffffffff8112a873: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135f90)
Location: kernel/futex.c:2779
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81135f90-ffffffff811363e1: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2801
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81141860-ffffffff81141cb3: futex_lock_pi (STB_LOCAL)
ffffffff81142aaa-ffffffff81142abd: futex_lock_pi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114d8d0)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114d8d0-ffffffff8114dd65: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115ce90)
Location: kernel/futex.c:2806
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115ce90-ffffffff8115d315: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159080)
Location: kernel/futex.c:2773
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81159080-ffffffff81159493: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b2d0)
Location: kernel/futex.c:2772
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115b2d0-ffffffff8115b72d: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117fdf0)
Location: kernel/futex.c:3018
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8117fdf0-ffffffff81180260: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b51c0)
Location: kernel/futex/pi.c:930
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811b51c0-ffffffff811b5615: futex_lock_pi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f62d0)
Location: kernel/futex/pi.c:930
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811f62d0-ffffffff811f6725: futex_lock_pi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120aad0)
Location: kernel/futex/pi.c:930
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff8120aad0-ffffffff8120af1d: futex_lock_pi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff81222030)
Location: kernel/futex/pi.c:918
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff81222030-ffffffff812224a4: futex_lock_pi (STB_GLOBAL)
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
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b9fa8)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffff8000101b9fa8-ffff8000101ba4a8: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0403c10)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c0403c10-c0404128: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0000000002218c0)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c0000000002218c0-c000000000221f08: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013faa8)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffe00013faa8-ffffffe00013ff5e: futex_lock_pi (STB_LOCAL)
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
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81145ef0)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81145ef0-ffffffff81146385: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81139200)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81139200-ffffffff8113968f: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81143da0)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81143da0-ffffffff81144235: futex_lock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int futex_lock_pi(u32 *uaddr, unsigned int flags, ktime_t *time, int trylock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114fe30)
Location: kernel/futex.c:2893
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114fe30-ffffffff811502ad: futex_lock_pi (STB_LOCAL)
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
