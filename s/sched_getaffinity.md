# Function: <code>sched_getaffinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae070)
Location: kernel/sched/core.c:4523
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_getaffinity
```
**Symbols:**

```
ffffffff810ae070-ffffffff810ae100: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0a80)
Location: kernel/sched/core.c:4773
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_getaffinity
```
**Symbols:**

```
ffffffff810b0a80-ffffffff810b0b10: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6c90)
Location: kernel/sched/core.c:4810
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_getaffinity
```
**Symbols:**

```
ffffffff810b6c90-ffffffff810b6d21: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2ee0)
Location: kernel/sched/core.c:4707
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_getaffinity
```
**Symbols:**

```
ffffffff810b2ee0-ffffffff810b2f71: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba2e0)
Location: kernel/sched/core.c:4751
Inline: False
Direct callers:
  - kernel/sched/core.c:SyS_sched_getaffinity
  - kernel/compat.c:compat_SyS_sched_getaffinity
```
**Symbols:**

```
ffffffff810ba2e0-ffffffff810ba371: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c18e0)
Location: kernel/sched/core.c:4886
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810c18e0-ffffffff810c1971: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cac10)
Location: kernel/sched/core.c:4871
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810cac10-ffffffff810caca1: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d28d0)
Location: kernel/sched/core.c:5324
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810d28d0-ffffffff810d2961: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcd40)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810dcd40-ffffffff810dcdd1: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5920)
Location: kernel/sched/core.c:5748
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810e5920-ffffffff810e59b1: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3540)
Location: kernel/sched/core.c:6572
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810e3540-ffffffff810e35d4: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e56d0)
Location: kernel/sched/core.c:6873
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810e56d0-ffffffff810e5764: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fc7b0)
Location: kernel/sched/core.c:8066
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x64_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810fc7b0-ffffffff810fc844: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81118de0)
Location: kernel/sched/core.c:8174
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff81118de0-ffffffff81118e8c: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811405e0)
Location: kernel/sched/core.c:8358
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff811405e0-ffffffff8114068c: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114c4a0)
Location: kernel/sched/core.c:8467
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff8114c4a0-ffffffff8114c54c: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81158160)
Location: kernel/sched/core.c:8478
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff81158160-ffffffff8115820f: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c808)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__arm64_sys_sched_getaffinity
  - kernel/compat.c:__arm64_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffff80001013c808-ffff80001013c8c4: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038cc10)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_getaffinity
```
**Symbols:**

```
c038cc10-c038cca4: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018af30)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__do_sys_sched_getaffinity
  - kernel/compat.c:__do_compat_sys_sched_getaffinity
```
**Symbols:**

```
c00000000018af30-c00000000018b020: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ebf9e)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__se_sys_sched_getaffinity
```
**Symbols:**

```
ffffffe0000ebf9e-ffffffe0000ec02c: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6f50)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810d6f50-ffffffff810d6fe1: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5840)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810c5840-ffffffff810c58d1: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3b90)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810d3b90-ffffffff810d3c21: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int sched_getaffinity(pid_t pid, struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810deb30)
Location: kernel/sched/core.c:5515
Inline: False
Direct callers:
  - kernel/sched/core.c:__ia32_sys_sched_getaffinity
  - kernel/sched/core.c:__x64_sys_sched_getaffinity
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
**Symbols:**

```
ffffffff810deb30-ffffffff810debd0: sched_getaffinity (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
