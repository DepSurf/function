# Function: <code>__do_compat_sys_rt_sigqueueinfo</code>

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
long int __do_compat_sys_rt_sigqueueinfo(compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a20d0)
Location: kernel/signal.c:3291
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810a20d0-ffffffff810a2138: __do_compat_sys_rt_sigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aa37f)
Location: kernel/signal.c:3618
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810af40f)
Location: kernel/signal.c:3866
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b5a2f)
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810bd2cf)
Location: kernel/signal.c:3892
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b864f)
Location: kernel/signal.c:3913
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b9bd0)
Location: kernel/signal.c:3935
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810cc1e0)
Location: kernel/signal.c:4023
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810e3268)
Location: kernel/signal.c:4006
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff811037a8)
Location: kernel/signal.c:4008
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8110f9e8)
Location: kernel/signal.c:4032
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff81119358)
Location: kernel/signal.c:4043
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (c00000000015976c)
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810afd9f)
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff8109e6bf)
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810af2ff)
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
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
In kernel/signal.c (ffffffff810b75cf)
Location: kernel/signal.c:3874
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigqueueinfo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
