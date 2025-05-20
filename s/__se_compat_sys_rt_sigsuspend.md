# Function: <code>__se_compat_sys_rt_sigsuspend</code>

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
In kernel/signal.c (ffffffff810a1470)
Location: kernel/signal.c:3887
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810a99f0)
Location: kernel/signal.c:4214
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810ac260)
Location: kernel/signal.c:4462
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810b2870)
Location: kernel/signal.c:4470
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810bb300)
Location: kernel/signal.c:4488
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810b65c0)
Location: kernel/signal.c:4525
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810b58a0)
Location: kernel/signal.c:4547
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810c7ea0)
Location: kernel/signal.c:4631
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810df07f)
Location: kernel/signal.c:4646
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810ffe3f)
Location: kernel/signal.c:4648
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff8110becf)
Location: kernel/signal.c:4672
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff8111587f)
Location: kernel/signal.c:4683
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffff80001010e720)
Location: kernel/signal.c:4470
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigsuspend
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
long int __se_compat_sys_rt_sigsuspend(long int unewset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155a30)
Location: kernel/signal.c:4470
Inline: False
```
**Symbols:**

```
c000000000155a30-c000000000155ae0: __se_compat_sys_rt_sigsuspend (STB_GLOBAL)
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
In kernel/signal.c (ffffffff810acbe0)
Location: kernel/signal.c:4470
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff8109b560)
Location: kernel/signal.c:4470
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810ac140)
Location: kernel/signal.c:4470
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
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
In kernel/signal.c (ffffffff810b42b0)
Location: kernel/signal.c:4470
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigsuspend
  - kernel/signal.c:__ia32_compat_sys_rt_sigsuspend
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
