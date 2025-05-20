# Function: <code>__se_compat_sys_rt_sigtimedwait_time64</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aabd7)
Location: kernel/signal.c:3427
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810afc68)
Location: kernel/signal.c:3556
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810b6288)
Location: kernel/signal.c:3561
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810b96d8)
Location: kernel/signal.c:3579
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810b4988)
Location: kernel/signal.c:3599
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810b64d8)
Location: kernel/signal.c:3621
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810c9368)
Location: kernel/signal.c:3709
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810e59b4)
Location: kernel/signal.c:3692
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff81106544)
Location: kernel/signal.c:3694
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff81112834)
Location: kernel/signal.c:3718
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff8111c224)
Location: kernel/signal.c:3729
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffff8000101124bc)
Location: kernel/signal.c:3561
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64
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
long int __se_compat_sys_rt_sigtimedwait_time64(long int uthese, long int uinfo, long int uts, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000159f00)
Location: kernel/signal.c:3561
Inline: False
```
**Symbols:**

```
c000000000159f00-c00000000015a02c: __se_compat_sys_rt_sigtimedwait_time64 (STB_GLOBAL)
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
In kernel/signal.c (ffffffff810b05f8)
Location: kernel/signal.c:3561
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff8109ef18)
Location: kernel/signal.c:3561
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810afb58)
Location: kernel/signal.c:3561
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
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
In kernel/signal.c (ffffffff810b7e28)
Location: kernel/signal.c:3561
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
