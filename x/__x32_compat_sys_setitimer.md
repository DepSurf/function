# Function: <code>__x32_compat_sys_setitimer</code>

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
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81123bd0)
Location: kernel/time/itimer.c:318
Inline: False
```
**Symbols:**

```
ffffffff81123bd0-ffffffff81123ca8: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112f2a0)
Location: kernel/time/itimer.c:317
Inline: False
```
**Symbols:**

```
ffffffff8112f2a0-ffffffff8112f378: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81139d10)
Location: kernel/time/itimer.c:317
Inline: False
```
**Symbols:**

```
ffffffff81139d10-ffffffff81139de2: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81145990)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff81145990-ffffffff81145a62: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
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
ffffffff81155909-ffffffff81155935: __x32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81155220-ffffffff8115535c: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
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
ffffffff81be3c13-ffffffff81be3c3f: __x32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff81151490-ffffffff811515cc: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
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
ffffffff81bd5b2b-ffffffff81bd5b58: __x32_compat_sys_setitimer.cold (STB_LOCAL)
ffffffff811528f0-ffffffff81152a3c: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
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
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113e140)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff8113e140-ffffffff8113e212: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81130c60)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff81130c60-ffffffff81130d32: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113be60)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff8113be60-ffffffff8113bf32: __x32_compat_sys_setitimer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_setitimer(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81148940)
Location: kernel/time/itimer.c:313
Inline: False
```
**Symbols:**

```
ffffffff81148940-ffffffff81148a12: __x32_compat_sys_setitimer (STB_GLOBAL)
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
