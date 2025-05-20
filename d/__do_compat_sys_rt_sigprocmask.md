# Function: <code>__do_compat_sys_rt_sigprocmask</code>

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
In kernel/signal.c (ffffffff810a179b)
Location: kernel/signal.c:2734
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810a9d1b)
Location: kernel/signal.c:2912
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810ac58b)
Location: kernel/signal.c:3041
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b2b9b)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810bb62b)
Location: kernel/signal.c:3064
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b68eb)
Location: kernel/signal.c:3084
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b5c0b)
Location: kernel/signal.c:3106
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810c820b)
Location: kernel/signal.c:3191
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810df3ea)
Location: kernel/signal.c:3171
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810ff72a)
Location: kernel/signal.c:3173
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff8110b76a)
Location: kernel/signal.c:3197
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff8111511a)
Location: kernel/signal.c:3208
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffff80001010ea30)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155dc0)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810acf0b)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff8109b88b)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810ac46b)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b45db)
Location: kernel/signal.c:3046
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
```
</details>
</li>
</ul>

## Differences
