# Function: <code>task_can_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae810)
Location: kernel/sched/core.c:5066
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810ae810-ffffffff810ae958: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b11e0)
Location: kernel/sched/core.c:5322
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810b11e0-ffffffff810b133a: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7460)
Location: kernel/sched/core.c:5356
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810b7460-ffffffff810b75a6: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3720)
Location: kernel/sched/core.c:5268
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810b3720-ffffffff810b378c: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba990)
Location: kernel/sched/core.c:5347
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810ba990-ffffffff810ba9fc: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1e00)
Location: kernel/sched/core.c:5472
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810c1e00-ffffffff810c1e69: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb130)
Location: kernel/sched/core.c:5455
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810cb130-ffffffff810cb199: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2dd0)
Location: kernel/sched/core.c:5907
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810d2dd0-ffffffff810d2e3e: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd260)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810dd260-ffffffff810dd2ce: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5e20)
Location: kernel/sched/core.c:6334
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810e5e20-ffffffff810e5e8c: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3b70)
Location: kernel/sched/core.c:7148
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810e3b70-ffffffff810e3bdc: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5b40)
Location: kernel/sched/core.c:7512
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810e5b40-ffffffff810e5bac: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fcc20)
Location: kernel/sched/core.c:8709
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810fcc20-ffffffff810fccac: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_effective_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81119570)
Location: kernel/sched/core.c:8992
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff81119570-ffffffff81119637: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_effective_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81140e50)
Location: kernel/sched/core.c:9182
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff81140e50-ffffffff81140f17: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114cb70)
Location: kernel/sched/core.c:9339
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_fork
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff8114cb70-ffffffff8114cb90: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81158830)
Location: kernel/sched/core.c:9326
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_fork
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff81158830-ffffffff81158850: task_can_attach (STB_GLOBAL)
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
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013cd48)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffff80001013cd48-ffff80001013cdd0: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038d1b4)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
c038d1b4-c038d230: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018b4a0)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
c00000000018b4a0-c00000000018b578: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec52e)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffe0000ec52e-ffffffe0000ec5ac: task_can_attach (STB_GLOBAL)
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
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7450)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810d7450-ffffffff810d74be: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5d70)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810c5d70-ffffffff810c5dde: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d40b0)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810d40b0-ffffffff810d411e: task_can_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int task_can_attach(struct task_struct *p, const struct cpumask *cs_cpus_allowed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df030)
Location: kernel/sched/core.c:6100
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
**Symbols:**

```
ffffffff810df030-ffffffff810df09e: task_can_attach (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask *cs_effective_cpus</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask *cs_cpus_allowed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct cpumask *cs_effective_cpus</code>
</li>
</ul>
</details>
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
