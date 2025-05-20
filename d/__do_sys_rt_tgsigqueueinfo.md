# Function: <code>__do_sys_rt_tgsigqueueinfo</code>

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
long int __do_sys_rt_tgsigqueueinfo(pid_t tgid, pid_t pid, int sig, siginfo_t *uinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f780)
Location: kernel/signal.c:3322
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
**Symbols:**

```
ffffffff8109f780-ffffffff8109f801: __do_sys_rt_tgsigqueueinfo (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a7a34)
Location: kernel/signal.c:3647
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810ae1f4)
Location: kernel/signal.c:3895
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b4804)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810bcd14)
Location: kernel/signal.c:3921
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b8034)
Location: kernel/signal.c:3942
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b95b5)
Location: kernel/signal.c:3964
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810cbbc5)
Location: kernel/signal.c:4052
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810e2d1b)
Location: kernel/signal.c:4035
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff811031db)
Location: kernel/signal.c:4037
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff8110f41b)
Location: kernel/signal.c:4061
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff81118d9b)
Location: kernel/signal.c:4072
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (c0369ad4)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (c00000000015815c)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffe0000d19ba)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810aeb74)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff8109d4c4)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810ae0d4)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
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
In kernel/signal.c (ffffffff810b6344)
Location: kernel/signal.c:3903
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__x64_sys_rt_tgsigqueueinfo
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
