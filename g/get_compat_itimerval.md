# Function: <code>get_compat_itimerval</code>

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
In kernel/compat.c (ffffffff811106ae)
Location: kernel/compat.c:290
Inline: True
Inline callers:
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
In kernel/compat.c (ffffffff81117dee)
Location: kernel/compat.c:290
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_setitimer
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
In kernel/compat.c (ffffffff8111f50e)
Location: kernel/compat.c:290
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_setitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120ac0)
Location: kernel/compat.c:226
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_setitimer
```
**Symbols:**

```
ffffffff81120ac0-ffffffff81120b36: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c1a0)
Location: kernel/compat.c:203
Inline: False
Direct callers:
  - kernel/time/itimer.c:compat_SyS_setitimer
```
**Symbols:**

```
ffffffff8112c1a0-ffffffff8112c216: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113aa60)
Location: kernel/compat.c:160
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff8113aa60-ffffffff8113aad6: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811462d0)
Location: kernel/compat.c:160
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff811462d0-ffffffff81146346: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151430)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff81151430-ffffffff811514a6: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d080)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff8115d080-ffffffff8115d0f6: get_compat_itimerval (STB_GLOBAL)
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
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cc8b0)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__arm64_compat_sys_setitimer
```
**Symbols:**

```
ffff8000101cc8b0-ffff8000101cca64: get_compat_itimerval (STB_GLOBAL)
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
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000236cc0)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__se_compat_sys_setitimer
```
**Symbols:**

```
c000000000236cc0-c000000000236d60: get_compat_itimerval (STB_GLOBAL)
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
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811556a0)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff811556a0-ffffffff81155716: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811489c0)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff811489c0-ffffffff81148a36: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153470)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff81153470-ffffffff811534e6: get_compat_itimerval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_itimerval(struct itimerval *o, const struct compat_itimerval *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160370)
Location: kernel/compat.c:93
Inline: False
Direct callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
**Symbols:**

```
ffffffff81160370-ffffffff811603e6: get_compat_itimerval (STB_GLOBAL)
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
