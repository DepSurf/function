# Function: <code>__se_compat_sys_getitimer</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8112358a)
Location: kernel/time/itimer.c:122
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
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
In kernel/time/itimer.c (ffffffff8112ec5a)
Location: kernel/time/itimer.c:120
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811396eb)
Location: kernel/time/itimer.c:120
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8114536b)
Location: kernel/time/itimer.c:115
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811556ea)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8115195a)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81152dda)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811773ea)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x64_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811ab8b9)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811eba29)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff81200159)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff812165f9)
Location: kernel/time/itimer.c:141
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffff8000101afc14)
Location: kernel/time/itimer.c:115
Inline: True
Inline callers:
  - kernel/time/itimer.c:__arm64_compat_sys_getitimer
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
long int __se_compat_sys_getitimer(long int which, long int it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (c0000000002144f0)
Location: kernel/time/itimer.c:115
Inline: False
```
**Symbols:**

```
c0000000002144f0-c00000000021458c: __se_compat_sys_getitimer (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113db1b)
Location: kernel/time/itimer.c:115
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113064b)
Location: kernel/time/itimer.c:115
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff8113b83b)
Location: kernel/time/itimer.c:115
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/itimer.c (ffffffff811482fb)
Location: kernel/time/itimer.c:115
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_getitimer
  - kernel/time/itimer.c:__ia32_compat_sys_getitimer
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
