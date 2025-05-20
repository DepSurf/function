# Function: <code>get_itimerval</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81154730)
Location: kernel/time/itimer.c:317
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff81154730-ffffffff811547d5: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81150980)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff81150980-ffffffff81150a25: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81151db0)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff81151db0-ffffffff81151e5d: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811762d0)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff811762d0-ffffffff8117637d: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ab5b0)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff811ab5b0-ffffffff811ab68c: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811eb800)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff811eb800-ffffffff811eb8dc: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811fff30)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff811fff30-ffffffff8120000c: get_itimerval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_itimerval(struct itimerspec64 *o, const struct __kernel_old_itimerval *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff812163d0)
Location: kernel/time/itimer.c:313
Inline: False
Direct callers:
  - kernel/time/itimer.c:__ia32_sys_setitimer
  - kernel/time/itimer.c:__x64_sys_setitimer
```
**Symbols:**

```
ffffffff812163d0-ffffffff812164ac: get_itimerval (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
