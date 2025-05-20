# Function: <code>__do_sys_rt_sigqueueinfo</code>

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
long int __do_sys_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fda0)
Location: kernel/signal.c:3281
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8109fda0-ffffffff8109fe17: __do_sys_rt_sigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a811e)
Location: kernel/signal.c:3607
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810ad9de)
Location: kernel/signal.c:3855
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b3ffe)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810bd17e)
Location: kernel/signal.c:3881
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b84fe)
Location: kernel/signal.c:3902
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b9a7f)
Location: kernel/signal.c:3924
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810cc08f)
Location: kernel/signal.c:4012
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810e31af)
Location: kernel/signal.c:3995
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff811036df)
Location: kernel/signal.c:3997
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8110f91f)
Location: kernel/signal.c:4021
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8111928f)
Location: kernel/signal.c:4032
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (0)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369a0c)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015789c)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1936)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810ae36e)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8109ccbe)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810ad8ce)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b5b1e)
Location: kernel/signal.c:3863
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigqueueinfo
  - kernel/signal.c:__x64_sys_rt_sigqueueinfo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
