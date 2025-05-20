# Function: <code>futex_unlock_pi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81102c32)
Location: kernel/futex.c:2496
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110a042)
Location: kernel/futex.c:2620
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111832)
Location: kernel/futex.c:2629
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81112eef)
Location: kernel/futex.c:2769
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111e495)
Location: kernel/futex.c:2913
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
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
In kernel/futex.c (ffffffff8112afad)
Location: kernel/futex.c:2895
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136e25)
Location: kernel/futex.c:2967
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2983
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8113fae0-ffffffff8113fe49: futex_unlock_pi (STB_LOCAL)
ffffffff81142990-ffffffff811429b6: futex_unlock_pi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114b6c0)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114b6c0-ffffffff8114ba3b: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115c4d0)
Location: kernel/futex.c:2997
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8115c4d0-ffffffff8115c702: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811588b0)
Location: kernel/futex.c:2944
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811588b0-ffffffff81158a84: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159b20)
Location: kernel/futex.c:2943
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81159b20-ffffffff81159de8: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117e920)
Location: kernel/futex.c:3189
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8117e920-ffffffff8117ec13: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b5620)
Location: kernel/futex/pi.c:1100
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811b5620-ffffffff811b5951: futex_unlock_pi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f6740)
Location: kernel/futex/pi.c:1100
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff811f6740-ffffffff811f6a71: futex_unlock_pi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120af30)
Location: kernel/futex/pi.c:1100
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff8120af30-ffffffff8120b25a: futex_unlock_pi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff812224c0)
Location: kernel/futex/pi.c:1112
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:do_futex
```
**Symbols:**

```
ffffffff812224c0-ffffffff812227fd: futex_unlock_pi (STB_GLOBAL)
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
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b8838)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffff8000101b8838-ffff8000101b8dd4: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0401ec8)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c0401ec8-c0402328: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021de40)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
c00000000021de40-c00000000021e4fc: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013de7a)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffe00013de7a-ffffffe00013e312: futex_unlock_pi (STB_LOCAL)
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
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81143ce0)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81143ce0-ffffffff8114405b: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811377d0)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff811377d0-ffffffff81137b45: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81141b90)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff81141b90-ffffffff81141f0b: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int futex_unlock_pi(u32 *uaddr, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114f150)
Location: kernel/futex.c:3084
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff8114f150-ffffffff8114f4e4: futex_unlock_pi (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
