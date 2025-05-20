# Function: <code>__ia32_compat_sys_setitimer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81123af0)
Location: kernel/time/itimer.c:318
Inline: False
```
**Symbols:**

```
ffffffff81123af0-ffffffff81123bc7: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112f1c0)
Location: kernel/time/itimer.c:317
Inline: False
```
**Symbols:**

```
ffffffff8112f1c0-ffffffff8112f297: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81139c30)
Location: kernel/time/itimer.c:317
Inline: False
```
**Symbols:**

```
ffffffff81139c30-ffffffff81139d01: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811458b0)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff811458b0-ffffffff81145981: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:382
Inline: False
```
**Symbols:**

```
ffffffff811558ae-ffffffff811558da: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81154f00-ffffffff8115503b: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:378
Inline: False
```
**Symbols:**

```
ffffffff81be3bb8-ffffffff81be3be4: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81151170-ffffffff811512ab: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:378
Inline: False
```
**Symbols:**

```
ffffffff81bd5ad3-ffffffff81bd5b00: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff811525b0-ffffffff811526fb: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:378
Inline: False
```
**Symbols:**

```
ffffffff81cb1e42-ffffffff81cb1e84: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81176b90-ffffffff81176cea: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:378
Inline: False
```
**Symbols:**

```
ffffffff81e633e9-ffffffff81e63426: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff811ac080-ffffffff811ac282: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:378
Inline: False
```
**Symbols:**

```
ffffffff8205bc37-ffffffff8205bc4c: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff811ec370-ffffffff811ec59f: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/itimer.c (0)
Location: kernel/time/itimer.c:378
Inline: False
```
**Symbols:**

```
ffffffff820da439-ffffffff820da44e: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81200aa0-ffffffff81200ccf: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:219
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff821b5db3-ffffffff821b5dc8: __ia32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81216f40-ffffffff8121716f: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113e060)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff8113e060-ffffffff8113e131: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81130b80)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff81130b80-ffffffff81130c51: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113bd80)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff8113bd80-ffffffff8113be51: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __ia32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81148860)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff81148860-ffffffff81148931: __ia32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>const struct pt_regs *__unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs *regs</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
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
