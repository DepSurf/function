# Function: <code>put_compat_itimerval</code>

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
In kernel/compat.c (ffffffff811105fb)
Location: kernel/compat.c:300
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_getitimer
  - kernel/compat.c:compat_SyS_setitimer
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
In kernel/compat.c (ffffffff81117e9a)
Location: kernel/compat.c:300
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_getitimer
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
In kernel/compat.c (ffffffff8111f5ba)
Location: kernel/compat.c:300
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_setitimer
  - kernel/compat.c:compat_SyS_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120b40)
Location: kernel/compat.c:239
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_setitimer
  - kernel/time/itimer.c:compat_SyS_getitimer
```
**Symbols:**

```
ffffffff81120b40-ffffffff81120ba6: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c220)
Location: kernel/compat.c:216
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_setitimer
  - kernel/time/itimer.c:compat_SyS_getitimer
```
**Symbols:**

```
ffffffff8112c220-ffffffff8112c286: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113aae0)
Location: kernel/compat.c:173
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff8113aae0-ffffffff8113ab46: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81146350)
Location: kernel/compat.c:173
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff81146350-ffffffff811463b6: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811514b0)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff811514b0-ffffffff81151516: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d100)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff8115d100-ffffffff8115d166: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cca68)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__arm64_compat_sys_setitimer
  - kernel/time/itimer.c:__arm64_compat_sys_getitimer
```
**Symbols:**

```
ffff8000101cca68-ffff8000101ccc14: put_compat_itimerval (STB_GLOBAL)
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
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236d60)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_compat_sys_setitimer
  - kernel/time/itimer.c:__se_compat_sys_getitimer
```
**Symbols:**

```
c000000000236d60-c000000000236e00: put_compat_itimerval (STB_GLOBAL)
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
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155720)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff81155720-ffffffff81155786: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148a40)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff81148a40-ffffffff81148aa6: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811534f0)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff811534f0-ffffffff81153556: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int put_compat_itimerval(struct compat_itimerval *o, const struct itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811603f0)
Location: kernel/compat.c:106
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
**Symbols:**

```
ffffffff811603f0-ffffffff81160456: put_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
