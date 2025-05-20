# Function: <code>core_sys_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81221830)
Location: fs/select.c:547
Inline: False
Direct callers:
  - fs/select.c:SyS_select
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
```
**Symbols:**

```
ffffffff81221830-ffffffff81221b13: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812494b0)
Location: fs/select.c:551
Inline: False
Direct callers:
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
**Symbols:**

```
ffffffff812494b0-ffffffff812497df: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125c4b0)
Location: fs/select.c:552
Inline: False
Direct callers:
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
**Symbols:**

```
ffffffff8125c4b0-ffffffff8125c7c0: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81269d30)
Location: fs/select.c:599
Inline: False
Direct callers:
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
**Symbols:**

```
ffffffff81269d30-ffffffff8126a044: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128c5d0)
Location: fs/select.c:598
Inline: False
Direct callers:
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
**Symbols:**

```
ffffffff8128c5d0-ffffffff8128c8e4: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b3ae0)
Location: fs/select.c:594
Inline: False
Direct callers:
  - fs/select.c:do_pselect
  - fs/select.c:do_pselect
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812b3ae0-ffffffff812b3e06: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c8d20)
Location: fs/select.c:619
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812c8d20-ffffffff812c9087: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e5780)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:__do_sys_pselect6
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812e5780-ffffffff812e5aa0: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f71a0)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812f71a0-ffffffff812f7546: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132fcc0)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8132fcc0-ffffffff8133007e: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133b610)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8133b610-ffffffff8133b9de: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81341ac0)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff81341ac0-ffffffff81341ecd: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138f480)
Location: fs/select.c:624
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8138f480-ffffffff8138f88d: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814105e0)
Location: fs/select.c:625
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff814105e0-ffffffff814109e8: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8149b2b0)
Location: fs/select.c:625
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8149b2b0-ffffffff8149b6b8: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814d0360)
Location: fs/select.c:625
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff814d0360-ffffffff814d094e: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81502ca0)
Location: fs/select.c:625
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff81502ca0-ffffffff8150328a: core_sys_select (STB_GLOBAL)
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
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a4530)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_select
```
**Symbols:**

```
ffff8000103a4530-ffff8000103a4908: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0585f58)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:do_pselect
  - fs/select.c:kern_select
```
**Symbols:**

```
c0585f58-c0586428: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049e0a0)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_select
```
**Symbols:**

```
c00000000049e0a0-c00000000049e61c: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026b4ea)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_select
```
**Symbols:**

```
ffffffe00026b4ea-ffffffe00026b79e: core_sys_select (STB_GLOBAL)
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
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ef780)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812ef780-ffffffff812efb26: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e03b0)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812e03b0-ffffffff812e0756: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ed590)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812ed590-ffffffff812ed936: core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int core_sys_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec64 *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fe590)
Location: fs/select.c:621
Inline: False
Direct callers:
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812fe590-ffffffff812fe940: core_sys_select (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *end_time</code> ➡️ <code>struct timespec64 *end_time</code>
</li>
</ul>
</details>
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
