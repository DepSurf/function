# Function: <code>__se_sys_rt_sigprocmask</code>

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
In kernel/signal.c (ffffffff810a15fd)
Location: kernel/signal.c:2703
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810a9b7d)
Location: kernel/signal.c:2881
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810ac3ee)
Location: kernel/signal.c:3010
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b29fe)
Location: kernel/signal.c:3015
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810bb48e)
Location: kernel/signal.c:3033
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b674e)
Location: kernel/signal.c:3053
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b5a6e)
Location: kernel/signal.c:3075
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810c806e)
Location: kernel/signal.c:3160
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810df30e)
Location: kernel/signal.c:3140
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810ff63e)
Location: kernel/signal.c:3142
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff8110b67e)
Location: kernel/signal.c:3166
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff8111502e)
Location: kernel/signal.c:3177
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffff80001010e8dc)
Location: kernel/signal.c:3015
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_rt_sigprocmask(long int how, long int nset, long int oset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0366834)
Location: kernel/signal.c:3015
Inline: False
```
**Symbols:**

```
c0366834-c03669a8: __se_sys_rt_sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_rt_sigprocmask(long int how, long int nset, long int oset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155c40)
Location: kernel/signal.c:3015
Inline: False
```
**Symbols:**

```
c000000000155c40-c000000000155d90: __se_sys_rt_sigprocmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_rt_sigprocmask(long int how, long int nset, long int oset, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf2a8)
Location: kernel/signal.c:3015
Inline: False
```
**Symbols:**

```
ffffffe0000cf2a8-ffffffe0000cf342: __se_sys_rt_sigprocmask (STB_GLOBAL)
```
</details>
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
In kernel/signal.c (ffffffff810acd6e)
Location: kernel/signal.c:3015
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff8109b6ee)
Location: kernel/signal.c:3015
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810ac2ce)
Location: kernel/signal.c:3015
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
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
In kernel/signal.c (ffffffff810b443e)
Location: kernel/signal.c:3015
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
