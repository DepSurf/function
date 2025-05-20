# Function: <code>do_futex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81102af0)
Location: kernel/futex.c:3043
Inline: False
Direct callers:
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
```
**Symbols:**

```
ffffffff81102af0-ffffffff81102fe3: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81109fa0)
Location: kernel/futex.c:3176
Inline: False
Direct callers:
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
```
**Symbols:**

```
ffffffff81109fa0-ffffffff8110a4c4: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111790)
Location: kernel/futex.c:3189
Inline: False
Direct callers:
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
```
**Symbols:**

```
ffffffff81111790-ffffffff81111cb4: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81112de0)
Location: kernel/futex.c:3364
Inline: False
Direct callers:
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
```
**Symbols:**

```
ffffffff81112de0-ffffffff811132e6: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111e380)
Location: kernel/futex.c:3515
Inline: False
Direct callers:
  - kernel/futex.c:SyS_futex
  - kernel/futex_compat.c:compat_SyS_futex
```
**Symbols:**

```
ffffffff8111e380-ffffffff8111e880: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112aca0)
Location: kernel/futex.c:3497
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
  - kernel/futex_compat.c:__x32_compat_sys_futex
  - kernel/futex_compat.c:__ia32_compat_sys_futex
```
**Symbols:**

```
ffffffff8112aca0-ffffffff8112b7a4: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136d10)
Location: kernel/futex.c:3577
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__x32_compat_sys_futex
  - kernel/futex.c:__ia32_compat_sys_futex
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81136d10-ffffffff81137262: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142010)
Location: kernel/futex.c:3615
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81142010-ffffffff811421e9: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114de90)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff8114de90-ffffffff8114e069: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115e730)
Location: kernel/futex.c:3780
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff8115e730-ffffffff8115e909: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a5a0)
Location: kernel/futex.c:3704
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff8115a5a0-ffffffff8115a779: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b920)
Location: kernel/futex.c:3701
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff8115b920-ffffffff8115baea: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81180970)
Location: kernel/futex.c:3932
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81180970-ffffffff81180b3d: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811b3ca0)
Location: kernel/futex/syscalls.c:85
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff811b3ca0-ffffffff811b3e9a: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811f4ce0)
Location: kernel/futex/syscalls.c:85
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff811f4ce0-ffffffff811f4eda: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff81209470)
Location: kernel/futex/syscalls.c:85
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81209470-ffffffff812096d6: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff81220400)
Location: kernel/futex/syscalls.c:84
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81220400-ffffffff8122065c: do_futex (STB_GLOBAL)
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
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bc010)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__arm64_sys_futex_time32
  - kernel/futex.c:__arm64_sys_futex
```
**Symbols:**

```
ffff8000101bc010-ffff8000101bc2a0: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0404350)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
**Symbols:**

```
c0404350-c04048f8: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c000000000222120)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__se_sys_futex_time32
  - kernel/futex.c:__se_sys_futex
```
**Symbols:**

```
c000000000222120-c0000000002223c8: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe000140140)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__se_sys_futex
```
**Symbols:**

```
ffffffe000140140-ffffffe000140282: do_futex (STB_GLOBAL)
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
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811464b0)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff811464b0-ffffffff81146689: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811397b0)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff811397b0-ffffffff81139989: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81144360)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81144360-ffffffff81144539: do_futex (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_futex(u32 *uaddr, int op, u32 val, ktime_t *timeout, u32 *uaddr2, u32 val2, u32 val3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81150ee0)
Location: kernel/futex.c:3867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
**Symbols:**

```
ffffffff81150ee0-ffffffff811510b9: do_futex (STB_GLOBAL)
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
