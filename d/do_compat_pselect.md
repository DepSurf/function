# Function: <code>do_compat_pselect</code>

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
In fs/compat.c (ffffffff8126565c)
Location: fs/compat.c:1348
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
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
In fs/compat.c (ffffffff81291975)
Location: fs/compat.c:1351
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
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
In fs/compat.c (ffffffff812a6705)
Location: fs/compat.c:1262
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
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
In fs/select.c (ffffffff8126a917)
Location: fs/select.c:1309
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
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
In fs/select.c (ffffffff8128d1bd)
Location: fs/select.c:1300
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct compat_timespec *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b3260)
Location: fs/select.c:1308
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
```
**Symbols:**

```
ffffffff812b3260-ffffffff812b3406: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c8320)
Location: fs/select.c:1320
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6
  - fs/select.c:__ia32_compat_sys_pselect6
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812c8320-ffffffff812c8434: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e4e90)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812e4e90-ffffffff812e4f96: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f68b0)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812f68b0-ffffffff812f69b6: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132e7e0)
Location: fs/select.c:1303
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff8132e7e0-ffffffff8132e966: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133a070)
Location: fs/select.c:1309
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff8133a070-ffffffff8133a1f6: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81340620)
Location: fs/select.c:1309
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff81340620-ffffffff813407a6: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138dff0)
Location: fs/select.c:1312
Inline: False
Direct callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff8138dff0-ffffffff8138e176: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140f300)
Location: fs/select.c:1313
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff8140f300-ffffffff8140f4ab: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81499ee0)
Location: fs/select.c:1313
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff81499ee0-ffffffff8149a08b: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814cefb0)
Location: fs/select.c:1313
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff814cefb0-ffffffff814cf15b: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff815018f0)
Location: fs/select.c:1313
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff815018f0-ffffffff81501a9b: do_compat_pselect (STB_LOCAL)
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
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a3c48)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__arm64_compat_sys_pselect6_time32
  - fs/select.c:__arm64_compat_sys_pselect6_time64
```
**Symbols:**

```
ffff8000103a3c48-ffff8000103a3d60: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049da10)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__se_compat_sys_pselect6_time32
  - fs/select.c:__se_compat_sys_pselect6_time32
  - fs/select.c:__se_compat_sys_pselect6_time64
  - fs/select.c:__se_compat_sys_pselect6_time64
```
**Symbols:**

```
c00000000049da10-c00000000049db9c: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eee90)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812eee90-ffffffff812eef96: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812dfac0)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812dfac0-ffffffff812dfbc6: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ecca0)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812ecca0-ffffffff812ecda6: do_compat_pselect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_compat_pselect(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, void *tsp, compat_sigset_t *sigmask, compat_size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fdca0)
Location: fs/select.c:1293
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
**Symbols:**

```
ffffffff812fdca0-ffffffff812fdda6: do_compat_pselect (STB_LOCAL)
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
<code>enum poll_time_type type</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct compat_timespec *tsp</code> ➡️ <code>void *tsp</code>
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
