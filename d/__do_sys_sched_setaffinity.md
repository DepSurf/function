# Function: <code>__do_sys_sched_setaffinity</code>

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
In kernel/sched/core.c (ffffffff810c17d1)
Location: kernel/sched/core.c:4870
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810cab01)
Location: kernel/sched/core.c:4855
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810d27c2)
Location: kernel/sched/core.c:5308
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810dcc32)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810e5812)
Location: kernel/sched/core.c:5732
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810e3432)
Location: kernel/sched/core.c:6556
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810e55c4)
Location: kernel/sched/core.c:6857
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810fc6a4)
Location: kernel/sched/core.c:8050
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff81118cb1)
Location: kernel/sched/core.c:8158
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff81140496)
Location: kernel/sched/core.c:8342
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff8114f846)
Location: kernel/sched/core.c:8451
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff8115b6f6)
Location: kernel/sched/core.c:8462
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffff80001013c788)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__arm64_sys_sched_setaffinity
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
In kernel/sched/core.c (c038cb28)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_sched_setaffinity(pid_t pid, unsigned int len, long unsigned int *user_mask_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018ae30)
Location: kernel/sched/core.c:5499
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
```
**Symbols:**

```
c00000000018ae30-c00000000018af10: __do_sys_sched_setaffinity (STB_LOCAL)
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
In kernel/sched/core.c (ffffffe0000ebf3c)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__se_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810d6e42)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810c5732)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810d3a82)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
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
In kernel/sched/core.c (ffffffff810dea22)
Location: kernel/sched/core.c:5499
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setaffinity
  - kernel/sched/core.c:__x64_sys_sched_setaffinity
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
