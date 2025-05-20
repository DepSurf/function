# Function: <code>__do_compat_sys_rt_tgsigqueueinfo</code>

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
long int __do_compat_sys_rt_tgsigqueueinfo(compat_pid_t tgid, compat_pid_t pid, int sig, struct compat_siginfo *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a2180)
Location: kernel/signal.c:3334
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff810a2180-ffffffff810a21fb: __do_compat_sys_rt_tgsigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aa3f5)
Location: kernel/signal.c:3658
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810af485)
Location: kernel/signal.c:3906
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b5aa5)
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810bced5)
Location: kernel/signal.c:3932
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b8135)
Location: kernel/signal.c:3953
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b96b9)
Location: kernel/signal.c:3975
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810cbcc9)
Location: kernel/signal.c:4063
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810e2dce)
Location: kernel/signal.c:4046
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff8110329e)
Location: kernel/signal.c:4048
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff8110f4de)
Location: kernel/signal.c:4072
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff81118e5e)
Location: kernel/signal.c:4083
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (c00000000015981c)
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810afe15)
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff8109e735)
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810af375)
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b7645)
Location: kernel/signal.c:3914
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__ia32_compat_sys_rt_tgsigqueueinfo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
